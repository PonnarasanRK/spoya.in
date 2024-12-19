# Spoya.in E-commerce Website

## Running the Server

1. Open a terminal in the `spoya.in` directory
2. Run the following command to start the server:
   ```bash
   node server.js
   ```
   This will start the server on port 5000 and serve both the API and static files.

3. In VS Code:
   - Click on the "Ports" tab in the bottom panel
   - Click "Forward a Port"
   - Enter "5000"
   - Copy the forwarded URL (it should look like `https://something-5000.devtunnels.ms`)
   - You can now access the website from any device using this URL

## Troubleshooting

If you see "Error loading products" on the products page:
1. Make sure the server is running (`node server.js`)
2. Check that port 5000 is forwarded in VS Code
3. Try refreshing the page
4. Check the error details shown on the products page for more information

Note: The server handles both the website files and the API from the same port (5000), so you only need to forward one port.
