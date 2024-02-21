#### [0.1.51] - 2024-02-20 8:30 GMT
![New blocks](https://i.ibb.co/GxpdfvJ/New-Blocks.png)
##### Added
- New blocks for event schedule agendas and frequently asked questions.
- Text blocks can be configured to display smart contract information by configuring the properties to read from smart contract function through the edit panel.

##### Fixed
- Code based simplified by removing unused dependencies and improved unit tests.

#### [0.1.47] - 2024-02-04 8:30 GMT
![Sharing](https://i.ibb.co/CMfVxhS/Capture.png)
##### Added
- You can now see how your project social sharing card would look like when publishing

##### Fixed
- Editing a selected element only applies to such element and does not permeate to other elements with the same class.
- Saving metadata for a project is now consistent and does not revert to default metadata values when refreshing the screen

#### [0.1.45] - 2023-12-19 6:30 GMT

New [Web3Modal](https://web3modal.com/) button for authentication, and temporal deprecation of the Web3Button in favor of the modal for interacting with smart contracts.
![Web3Modal](https://i.ibb.co/Zx07dCW/web3modal.png)
##### Added
- New connect wallet button
- New documentation (WIP) available for every component and accessible via the component editor modal (information icon)

##### Changed
- Webstudio SDK now uses ethers 6.9.0 and web3modal 3.4.0
- Web3 form now enables uploading ABI and selecting method to interact via dropdown, instead of copy pasting the abi json and the method name

##### Fixed
- Login with Wallet Connect

##### Removed
- Web3Button temporarily removed. We will focus on more specific components such as NFT galleries and Stores.

#### [0.1.41] - 2023-11-28 12:21 GMT

Now you copy and paste across pages in your project with the clipboard functionality! Let it be that you want to clone an existing page or duplicate a header or a section in multiple pages! 1. Select your component, 2. Copy to clipboard, 3. Select a destination component and paste from clipboard!
![Clipboard](https://i.ibb.co/yh522Wv/Clipboard.png, "Clipboard") 
##### Added
- [Clipboard](https://twitter.com/webstudioso/status/1729472757581185305). Now you can copy and paste across pages in your project with the clipboard function. Simply select your item (it could be a whole page), copy to clipboard, select a destination component and click on paste from clipboard.
- New template "Wellness"
##### Changed
- Toolbar iconography

#### [0.1.35] - 2023-10-23 14:00 GMT

New style manager editor for borders that allows you to define in a visual way, the radius and shape for the borders of your selected component.
!["Border Radius Editor](https://i.ibb.co/Sy7MXF1/Border-Radius.gif, "Border Radius Editor") 

#### [0.1.34] - 2023-09-19 03:10 GMT
🚀 New options for styling borders in text elements and fixed the issue that did not allow editing text fields
##### Added
- New options to change border styles for text fields on the style manager.

##### Fixed
- Fixed an issue not allowing users to edit the text inside text fields.

#### [0.1.32] - 2023-09-04 09:20 GMT

🚀 Launching today, a responsive and easy mechanism to style and positions components freely, anywhere in the screen by simply dragging.
!["Drag and Drop and Style Manager](https://i.ibb.co/fpgs17S/Anim.png, "Drag and Drop and Style Manager") 
##### Added
- ["Drag and Drop and Style Manager](https://twitter.com/webstudioso/status/1698613369098354921). Now you can drag items anywhere in the screen beyond the grid lines giving you more freedom to position items, respecting device resolution.
- Style manager (Text components). Now text components can be styled using the new style manager interface, more similar to what WIX offers, it provides easy ways to change and edit text, font, add animations or links to current text components. We will be rolling out this interface for other component types in the future.
- Functionality to "bring to front" and "move to back" overlapping components
- Animate CSS new animation mechanism
- New link generation from text mechanism
##### Removed
- Prima Persona and Streamer templates were removed due to compliance issue.
##### Changed
- You can now drag and drop any item anywhere in the canvas

#### [0.1.31] - 2023-07-19 15:30 GMT

🚀 Launching today, Studio AI template preview. Build incredible landing pages for your Webstudio projects by just describing them! Powered by ChatGPT
![Studio AI Preview](https://i.ibb.co/kmhkHVB/Screenshot-2023-07-28-162617.png, "Studio AI Preview") 
##### Added
- [Studio AI Preview](https://twitter.com/webstudioso/status/1684894684819107840). Build websites without writing any code, just describe your project and the website characteristics and have Webstudio AI build it for you using TailwindCSS. 
 
##### Changed
- Studio AI is available in the free plan (limited use)
- All Web3 blocks are available in free plan

#### [0.1.29] - 2023-07-14 9:55 GMT

Adding capabilities to set an image as component background.

![Background](https://i.ibb.co/6bZtkXd/Untitled.png, "Background") 
##### Added
- [Background Images](https://github.com/orgs/webstudioso/projects/1/views/1?pane=issue&itemId=33281542) To change a background image select a component and then open the media section and select the desired image. To edit further the properties of the background (alignment, width, etc) click on edit icon in the menu bar on the component and scroll down to the decorations section. [Check out this demo tutorial for a step by step](https://twitter.com/webstudioso/status/1679784701832118273)
 

#### [0.1.28] - 2023-07-03 14:45 GMT

Introducing the Changelog. This is a notification window that will be shown to users when opening the editor, if there are novelties, such as new launched features, fixes, ongoing issue tracking, etc.  
![Changelog](https://i.ibb.co/jzRsz2T/Screenshot-2023-07-03-at-14-22-59.png, "Changelog") 
##### Added
- [Changelog Window](https://github.com/orgs/webstudioso/projects/1?pane=issue&itemId=30367337) Get notified of all the changes and events in the platform, including new features, fixes, addons, ongoing issues.  
 
##### Changed
- Slightly increased automated test coverage as part of our Operational Excellence goals


