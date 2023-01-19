# GraphLinq Server Relay For Chat-GPT / OpenAI

This server accepts a `POST` request to `/chat`, and uses the server's API Key and IP address to pass the query to the openai API. By running multiple instances spread out to geographically separate servers, would allow for load balancing.

## Install

`git clone git@github.com:GraphLinq/GraphLinq.ServerRelayOpenAI.git`

`yarn`

## Settings

Edit `server.js` and set your API Key `const configuration = new Configuration({apiKey: "",});`.

## Optional

Edit `server.js` and change `const port = 9021;` to the port you would like to use.

## Running

`yarn start`

![Screenshot of Server running](screenshot.png "Server Running")
