# repo-34-image-generation-DALL-E
we r creating a web app for genrating image using api key


#to run this code , our openai library will be "openai==0.28"     , this is must

# pip install openai

#to run the streamlit 
streamlit run "dalle - image generation - web app.py"
to stop the code ctrl+c



#if our openai library grater than version this error we will get:

APIRemovedInV1: You tried to access openai.Image, but this is no longer supported in openai>=1.0.0 - see the README at https://github.com/openai/openai-python for the API. You can run `openai migrate` to automatically upgrade your codebase to use the 1.0.0 interface. Alternatively, you can pin your installation to the old version, e.g. `pip install openai==0.28` A detailed migration guide is available here: https://github.com/openai/openai-python/discussions/742
Traceback:

File "C:\Users\poppo\anaconda3\envs\mlproj\lib\site-packages\streamlit\runtime\scriptrunner\script_runner.py", line 565, in _run_script
    exec(code, module.__dict__)
File "C:\Users\poppo\Desktop\github ai\end to end by vivek\repo-34-image-generation-DALL-E\dalle - image generation - web app.py", line 42, in <module>
    generated_img = generate_image(img_description)
File "C:\Users\poppo\Desktop\github ai\end to end by vivek\repo-34-image-generation-DALL-E\dalle - image generation - web app.py", line 18, in generate_image
    img_response = openai.Image.create(
File "C:\Users\poppo\anaconda3\envs\mlproj\lib\site-packages\openai\lib\_old_api.py", line 39, in __call__
    raise APIRemovedInV1(symbol=self._symbol)
ChatGPT