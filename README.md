# Orzo-OpenAI
Visualize with an OpenAI assistant in Orzo!
To use this version of orzo, replace your window.py file in Orzo-Main/orzo/window.py with GPT-window.py. Renaming it to window or changing import statements will be neccesary.
This version currently supports streaming, more information can be found here: https://platform.openai.com/docs/assistants/overview
The Assistants API is dynamic and will change in the future. 
Modification to GPT-window.py will likely be neccesary, specifically the send_to_chat(self, user_input) method

The custom function Invoke_Method's JSON file is available in this repository as an example of a custom function definition.
Assitants can be created in text, but this implementation utilized the Assistants playground, so only an assistants key is required in this code.

## Example
In this example, a user chats with an OpenAI Assistant to invoke multiple methods with custom parameters.

Methods are defined the the creation of a Rigatoni server.

Activate the conversation:
![ChatBox](https://github.com/InsightCenterNoodles/Orzo-OpenAI/blob/main/Orzo_chatbox.png)

Both methods invoked:
![Result](https://github.com/InsightCenterNoodles/Orzo-OpenAI/blob/main/ChatGPTrobotdemo.png)

## Authors

* **Jonny Bachman**  [paulcena2](https://github.com/paulcena2)
* **Harold MacArthur**  [f1shkabob](https://github.com/f1shkabob)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
