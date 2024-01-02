# A Node.js Script for Pterodactyl Panel that deletes all suspended servers
This Node.js script is designed for use with the Pterodactyl Panel, a web-based game server management platform. The primary purpose of this script is to automate the removal of all suspended servers within the panel. It employs the Axios library, a popular HTTP client for Node.js, to interact with the Pterodactyl API.

### **Key Features:**

- Suspended Server Deletion: The script fetches information about all servers in the Pterodactyl Panel and identifies those that are in a suspended state.

- Axios Library: Utilizes the Axios library to make HTTP requests to the Pterodactyl API endpoints, facilitating seamless communication with the panel.

- User Interaction: The script prompts the user for confirmation before proceeding with the deletion of suspended servers. This ensures a deliberate and controlled execution of the server deletion process.

## **Requirements:**
- Admin API key: You'll need to have a Admin API key in order to use this. (*Use this [link](https://docs.northdevelopment.tech/other-guides/getting-api-key-from-ptero) to generate an api key*)

## How to use:
- **Step 1:** Drop your Admin API key and Panel url in the [config](https://github.com/Luxerate/delete-suspended-servers/blob/main/config.json) file.
- **Step 2:** Run **node index.js**.
