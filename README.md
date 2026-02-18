# Programming with the Python OpenAI Generative AI APIs and an Intro to the OpenAI Agents SDK: A Full-Throttle, Code-Intensive Presentation with Paul Deitel

**This course is under development.** The first offering will be in June 2026. Once completed, the course's examples will be maintained in this repository.

---

## Getting an OpenAI API Key
Setting up your OpenAI Developer Account and securely storing your API Key is essential for interacting with the OpenAI APIs. 

### Step 1: Get an OpenAI Developer Account

#### Signup
Sign up for a developer account at https://platform.openai.com/signup

Additional relevant info:
* Pricing: For information on API pricing, visit https://openai.com/api/pricing/ 
* Rate Limits: You may also want to review the rate limits documentation at https://platform.openai.com/docs/guides/rate-limits/rate-limits 

### Step 2: Get an OpenAI Developer API Key
1. Sign into your account at https://platform.openai.com/docs/overview 
2. In the upper-right corner, press the settings icon 
3. In the left column under the **Project** heading, select **API keys**  
4. Press **+ Create new secret key**
5. Optionally, specify an API key **Name**, then press the **Create secret key** button 
6. Press the **Copy** button to copy the alphanumeric key to the clipboard—you'll use this in the next step


### Step 3: Storing the API Key as an Environment Variable

OpenAI recommends storing your API key in the environment variable `OPENAI_API_KEY` rather than directly in your code

#### Storing the API Key in macOS
1. Open **Terminal**
2. Open the configuration file `~/.zshrc` using a text editor (e.g., `nano ~/.zshrc`)
   ```bash
   nano ~/.zshrc
   ```
3. Scroll to the end of the file and add the following line, replacing `YourAPIKey` with the API key you copied to the clipboard in Step 2
   ```bash
   export OPENAI_API_KEY="YourAPIKey"
   ``` 
4. Save and close the file
5. Apply the changes:  
   ```bash
   source ~/.zshrc
   ``` 

#### Storing the API Key on Windows

1. In the taskbar’s **Search** field, enter `SystemPropertiesAdvanced`, and press *Enter* 
2. In the **System Properties** dialog, press **Environment Variables…**  
3. Under **User variables**, press **New…**
4. Enter the **Variable name** as `OPENAI_API_KEY` 
5. For **Variable value**, paste your API key from the clipboard
6. Press **OK** to save the environment variable, then **OK** again to close the **System Properties** dialog
7. Restart your command line before launching iPython or Jupyter Lab to ensure the new variable is loaded

---

# Execution Environment 
## Anaconda
**Coming soon**

## Docker
**Coming soon**

## Zero-Install MyBinder.org Environment
**Coming soon**

