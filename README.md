
#  Discord Group Disconnector 

A **fun trolling tool** that allows you to disconnect your friends from Discord groups by **continuously changing the group's region**. 

 **Note**: This tool is meant for **entertainment purposes only**. Please use it responsibly and adhere to Discord's guidelines!

---

##  Features

- Choose from various regions:
  - `brazil`, `hongkong`, `india`, `japan`, `us-central`, etc.
-  **Mix Mode**: Randomly changes the region to truly confuse your friends!
-  **Custom Interval**: Set how often the region is changed.
-  **Easy Stop**: Stop the process anytime with a single button.
-  Modern dark **GUI design**.

---

##  Installation

1. **Install Python**: Make sure [Python 3.11+](https://www.python.org/) is installed.
2. **Install dependencies**:
   ```bash
   pip install customtkinter requests
   ```
3. **Run the script**:
   ```bash
   python group.py
   ```

---

##  Demo

###  Screenshots

![Gui Preview](https://imgur.com/431xeFT.png)
![Token Input](https://imgur.com/kt7gWHF.png)

###  Video

  [**Watch the Video**](https://youtu.be/SbV-q_Y864o)

---

##  How to Use

1. Start the application.
2. Enter your **Discord Token** and the **Group ID**.  
    **Note**: Learn how to get your token [here](https://discordhelp.net/discord-token).  
3. Select a region or enable **Mix Mode** to randomly switch regions.
4. Set the **interval** using the slider (e.g., every 1 second).
5. Click `Change Region` to start the process.
6. When done, click the `Stop` button.

---

##  Notes

- Available regions:
  ```text
  brazil, hongkong, india, japan, rotterdam, russia,
  singapore, south-korea, southafrica, sydney,
  us-central, us-east, us-south, us-west
  ```
- **Rate Limit**: If Discord blocks changes due to rate limits, the tool will automatically wait until the limit resets.

---

##  FAQ

### How do I find the Group ID?
1. Go to Discord settings and enable **Developer Mode**.
2. Right-click on the group and select `Copy ID`.

### Is this tool safe?
- This tool uses your **token** to send requests to the Discord API. Make sure to run it only on your computer and never share your token with others!

---

##  Support

If you enjoy this tool, leave a on [GitHub](#) or share it with your friends!
