<img width="1788" height="1236" alt="image" src="https://github.com/user-attachments/assets/68f85285-e405-43d2-a65a-9c694af2ea50" />


### **How to Setup video [[YouTube]](https://www.youtube.com/watch?v=N7UKXkSbE84)**


# Honkai: Star Rail Bone-Based Facial Rig Script (Beta)

## Overview

This is a beta release of a script designed to apply isaac's bone-based facial rig directly to Honkai: Star Rail FBX character models.

The primary goal of this implementation is to provide a reliable, single-click solution for facial rigging.

## Key Features & Advantages

* **Direct Bone Generation:** The rig is generated directly onto the character's existing bone structure, rather than being bound to a separate control object.
* **Position Stability:** This approach eliminates inconsistencies and bugs related to the face's position that can occur with conventional methods.
* **One-Click Setup:** The entire implementation process is completed with a single click, allowing for extremely quick setup.

## Current Status and Known Issues

**⚠️ Beta Version:** This script is being released as a beta version for now.

The implementation of the animation data referenced by this script is still nascent. Depending on the character it is run on, the resulting facial expressions might be inferior to what is expected with the original isaac FaceRig.

**Specific Issue (Eyelids):** The main limitation concerning the animation implementation relates specifically to **eyelid movement**.

## Tested Models

The distributed facial rig was initially designed for **Maid models**, and these models (such as **Firefly** and **March 7th**) appear to be the best match for the rig.

Confirmed operation on other model types includes:

* **Kid** (Tribbie)
* **Lad** (Sunday)

## Usage Tips

* **Report Issues:** Operation has not been confirmed on all available characters. Please write a report if you encounter any issues to help improve future releases.
* **Eyelid Functionality:** Due to the nascent animation data, the eyelid function might be best suited for use with **Shape Keys** (morph targets) for better results.
* **Other Functions:** Other essential facial functions, such as the Eye Tracker, mouth movements, eyebrows, and group-based bone movements, appear to be working well at a glance.

## References

The following Discord links are provided for context on the source and development:

* **Release Reference:** [Discord Link](https://discord.com/channels/894925535870865498/1229767569674600481/1229767569674600481)
* **Source Face Rig:** [Discord Link](https://discord.com/channels/894925535870865498/1017222651632177152/1219675517029187736)
* **WIP/Development:** [Discord Link](https://discord.com/channels/894925535870865498/1298574741233471519/1449469416885588069)
