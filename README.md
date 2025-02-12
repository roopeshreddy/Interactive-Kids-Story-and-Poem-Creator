# Interactive Story and Poem Generator for Kids

This project features an engaging and interactive application designed to generate short stories or poems for children, paired with imaginative images. It leverages the capabilities of a Large Language Model (LLM), specifically utilizing the OpenAI API with the GPT-4o model to create rich and whimsical text. Additionally, it employs DALL-E to produce captivating visuals that complement the narrative.

## Features

>Story and Poem Generation: Automatically generates creative and age-appropriate stories or poems using GPT-4o.

>Image Creation: Generates imaginative visuals for the text using DALL-E, enhancing the storytelling experience.

>Interactive Interface: Provides a user-friendly interface for kids to input themes or keywords for personalized stories or poems.

## Task is to create a Python program that does the following:

>Ask for a theme or topic they'd like the poem/story to be about (e.g., "a magical forest," "a friendly dragon," "an adventure on the moon").

>(Optional) Ask for a specific element they want in image (e.g. boy, girl, school, park etc)

>Use the user's input to craft a prompt for the OpenAI API.

>Make a call to the OpenAI API (using the openai Python library) to generate a short poem or story suitable for kids based on the prompt.

>Ensure the generated text is age-appropriate, imaginative, and engaging.

>Craft a descriptive prompt for DALL-E based on the generated poem/story.

>Use the DALL-E API to generate an image that visually represents the text.

>Consider elements like style (e.g., "cartoon," "watercolor") and aspect ratio in your DALL-E prompt.

>Print the generated poem/story to the console.

>Display the generated image. You can use libraries like PIL (Pillow) or matplotlib to show the image within your Python environment or save it and open it in a separate window.

>Stream lit Application to take user input and give a pdf output of the poem/story
