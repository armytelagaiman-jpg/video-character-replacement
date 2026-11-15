# Video Character Replacement — Interactive Prototype v0.2

Static browser prototype for a guided character-replacement prompt workflow.

## Character Sheet flow
- Choose the visual style first.
- Choose whether to use a Character Sheet.
- If yes, the prototype creates a ready-to-copy Character Sheet prompt based on the selected style, uploaded reference photos, and outfit choice.
- Copy the prompt into Gemini or another external image-generation app and attach the same reference photos there.
- Upload the generated Character Sheet back into the prototype and explicitly approve it before proceeding to the final video prompt.

## Important limitations
- The prototype only previews local files in the browser and generates text prompts.
- It does not generate images or videos, edit video, perform AI image/video analysis, or upload files to a server.
- No OpenAI API key or paid API is required.
- Actual image generation and video editing happen in external applications.

## Run
Open `index.html` in a modern browser. For best clipboard support, use an HTTPS-hosted version (such as GitHub Pages).
