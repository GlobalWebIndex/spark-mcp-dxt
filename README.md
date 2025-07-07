# Claude desktop Extension builder for Spark MCP

Build Claude Desktop Extension for Spark MCP using mcp-remote

# How to build the extension

1. Clone the repo

   ```bash
   git clone https://github.com/GlobalWebIndex/spark-mcp-dxt.git
   ```

2. Run `npm` install
   ```bash
   npm install
   ```

3. Build the `.dxt` file
   ```bash
   npm run build
   ```

   > The output contains the location of the extension file `/path/to/spark-mcp-dxt.dxt`

# How to deploy to Claude

1. Open the folder where the file is located and double click it. If prompted choose to open it with `Claude desktop app`

2. When Claude desktop settings is opened click on the `Install` button:

   <img width="642" alt="image" src="https://github.com/user-attachments/assets/191313a1-30b8-4096-8fdf-fd20217942b4" />

4. Input your Spark API token in the required field and click the `Save` button:
   
   <img width="873" alt="image" src="https://github.com/user-attachments/assets/ae70eb59-cecd-40f7-bdc1-0d1d07c96b16" />

6. Enable the extension:
   
   <img width="604" alt="image" src="https://github.com/user-attachments/assets/22966623-164b-4287-865d-9488f3419d24" />

8. Start using the GWI MCP tools in Claude chat

# Use the released extension

1. Navigate to [releases](https://github.com/GlobalWebIndex/spark-mcp-dxt/releases)
2. Download the latest `spark-mcp-dtx.dtx` file from release assets
   <img width="914" alt="image" src="https://github.com/user-attachments/assets/23c6177c-5b17-4ffe-93f2-fc85eed78155" />

4. Follow the steps from [How to deploy to Claude](#how-to-deploy-to-claude)
