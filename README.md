# PE Sourcing Render MCP Server

MCP (Model Context Protocol) server for managing the PE Deal Sourcing pipeline on Render.

## Features

- **trigger_build**: Start new deployments of the pipeline
- - **check_deployment_status**: View recent deployment history and status
  - - **get_environment_variables**: List all current environment variables
    - - **update_environment_variable**: Modify or create environment variables
      - - **get_service_details**: Retrieve complete service configuration
        - - **get_recent_runs**: Summarize pipeline execution attempts over time
          - - **configure_schedule**: Adjust the cron schedule for automated runs
           
            - ## Setup
           
            - ### Prerequisites
           
            - - Node.js 18+
              - - npm
                - - Render API key (from your Render dashboard)
                  - - Render service ID for the PE sourcing pipeline
                   
                    - ### Installation
                   
                    - 1. Clone this repository
                      2. 2. Install dependencies: `npm install`
                         3. 3. Build the TypeScript: `npm run build`
                           
                            4. ### Configuration
                           
                            5. Set these environment variables:
                           
                            6. ```bash
                               export RENDER_API_KEY="your_render_api_key_here"
                               export RENDER_SERVICE_ID="crn-d6rva6fpm1nc73dqspi0"
                               ```

                               ### Running

                               ```bash
                               npm start
                               ```

                               ## License

                               MIT
