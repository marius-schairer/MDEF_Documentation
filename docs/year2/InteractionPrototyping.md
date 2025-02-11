<div class="breadcrumb">
    <a href="/">Home</a> <span class="breadcrumb-separator">/</span> 
    <a href="/year2">Year 2</a> <span class="breadcrumb-separator">/</span> 
    <span>Interaction Prototyping</span>
</div>

# LLUM 2025

![Cover Image](../images/Cover/InteractionPrototyping.png)

## Reflection
During the LLUM Barcelona festival, we had the opportunity to explore interactive installations and develop our own concepts. Working with light as a medium opened up new perspectives on how to create engaging public experiences.

## Project Description
Our installation focuses on creating an interactive light experience that responds to movement and sound. The concept revolves around making visible the invisible connections between people in public spaces.

## Concept
The questions displayed on a huge screen relate to faculty research, and participants' answers feed an accessible database of collective data and image artifacts created through user input using a multilingual transcription model and further processing and generative AI steps.

Alongside countless playful visualizations and visions of the future, we could see a common tone towards a hopeful future that achieves possibilities through technology-driven systems and sustainable ways of living in shared habitats with other species. 

It was a challenge to run this installation with moderate power consumption in an outdoor environment using the internet and a standard windows computer. Along the way of developing a robust interactions model based on various programming languages, we were able to gain some insights into different AI models and no-code approaches that could achieve similar results in the future. 

## Technical Implementation

<div style="display: flex; justify-content: left; margin: 20px 0;">
    <iframe 
        width="70%" 
        height="500" 
        src="https://www.youtube.com/embed/wrTFjlEQWVI?autoplay=1&mute=1&loop=1&playlist=wrTFjlEQWVI" 
        title="Project Demo" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</div>

## Installation
The installation ran on an Intel NUC. By outsourcing the generative tasks to APIs, it was possible to avoid the need for a powerful graphics processor.  

The process: **1 question → 3 inputs → 1 output.  

To ensure a smooth experience in a public space, several steps were required:  
- **Audio filtering** detected volume and transcribed speech.  
- **Content moderation** replaced inappropriate words with emojis before the input was displayed on the public screen.  
- An **LLM-generated description** enriched the input, which was then visualized by an image generation model.  

The system communicated with an ESP32 over local WiFi to control LED animations on the microphone that displayed process steps with colors and countdowns. A local website displayed the interface while synchronized with the main script.  

Finally, the data was uploaded to Supabase for archiving and online capture of all inputs.  

The code is open source, but still needs to be refined and documented. If you have any questions, please feel free to contact!  


## Testing & Results

<div style="display: flex; justify-content: left; margin: 20px 0;">
    <div style="width: 500px; height: 500px;">
        <iframe 
            width="100%" 
            height="100%" 
            src="https://www.youtube.com/embed/ZW35Tzpu3gU?autoplay=1&mute=1&loop=1&playlist=ZW35Tzpu3gU" 
            title="Testing Results" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>
    </div>
</div>

## Future Development
- Enhance responsiveness
- Add more interaction patterns
- Scale up for larger installations
