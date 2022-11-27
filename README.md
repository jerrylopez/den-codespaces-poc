<h3 align="center">Den in Codespaces (Proof of Concept)</h3>

<p align="center">This repo demenstrates a Magento 2 development environment running using <a href="https://github.com/swiftotter/den">Den</a> and <a href="https://github.com/features/codespaces">GitHub Codespaces</a>.</p>

<hr />

### Try it out!

Use the steps below to get a development environment up and running!

1. Click the green "Code" button.
2. Switch to the Codespaces tab.
3. Click the green "Create codespace on main" button. 

After following the steps above your Codespace will be created and a postStartCommand is ran to initialize your Den environment. To view the output of the `den bootstrap` command you can hit `CMD + SHIFT + P` to open the command pallete and type in "View Creation Log" to see a live update of the postStartCommand's output.

Once the postStartCommand is complete you'll be able to view your Magento store running in your Codespace! To find the URL go to the ports tab and click the globe icon by hovering over the port labeled `magento`. After clicking the icon a new tab will open and you will see your Magento store.
