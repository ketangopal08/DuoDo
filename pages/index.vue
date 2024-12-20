<script setup lang="ts">
import { Accordion, AccordionContent, AccordionItem, AccordionTrigger } from '@/components/ui/accordion'
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <header class="bg-white dark:bg-gray-800 shadow px-4 py-2">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-lg font-semibold">Page Title</h1>
        <nav>
          <ul class="flex space-x-4">
            <li><a href="#" class="hover:text-blue-600">Home</a></li>
            <li><a href="#" class="hover:text-blue-600">About</a></li>
            <li><a href="#" class="hover:text-blue-600">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>
    <main class="flex-grow container mx-auto px-4 py-6">
       <div class="flex flex-col sm:gap-4 sm:py-4 sm:pl-14">
    <Accordion type="single" collapsible>
    <AccordionItem value="item-2">
      <AccordionTrigger>Is it accessible?</AccordionTrigger>
      <AccordionContent>
        Yes. It adheres to the WAI-ARIA design pattern.
      </AccordionContent>
    </AccordionItem>
    <AccordionItem value="item-1">
      <AccordionTrigger>Is it accessible?</AccordionTrigger>
      <AccordionContent>
        Yes. It adheres to the WAI-ARIA design pattern.
      </AccordionContent>
    </AccordionItem>
    <AccordionItem value="item-4">
      <AccordionTrigger>Is it accessible?</AccordionTrigger>
      <AccordionContent>
        Yes. It adheres to the WAI-ARIA design pattern.
      </AccordionContent>
    </AccordionItem>
  </Accordion>
  </div>
    </main>
    <footer class="bg-white dark:bg-gray-800 shadow px-4 py-2">
      <div class="container mx-auto text-center">
        <p class="text-sm">&copy; 2024 Your Company. All rights reserved.</p>
      </div>
    </footer>
  </div>
  
</template>