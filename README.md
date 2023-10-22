<a href="https://graphqlexplorer.vercel.app">
  <img alt="https://graphqlexplorer.vercel.app" src="https://github.com/geobde/graphqlexplorer/blob/main/explorer.gif">
  <h1 align="center">GraphQL Explorer</h1>
</a>

<p align="center">
  A project that simplifies the process of generating queries from plain text prompts. <br />It harnesses the power of AI to make querying your GraphQL APIs a breeze.
</p>

<p align="center">
  <a href="https://twitter.com/geobde/status/1715527036846973048">
    <img src="https://img.shields.io/twitter/follow/geobde?style=flat&label=%graphqlexplorer&logo=twitter&color=0bf&logoColor=fff" alt="Twitter" />
  </a>
  <a href="https://github.com/geobde/graphqlexplorer/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/geobde/graphqlexplorer?label=license&logo=github&color=f80&logoColor=fff" alt="License" />
  </a>
</p>

<p align="center">
  <a href="#how-it-works"><strong>How It Works</strong></a> ·
  <a href="#quickstart"><strong>Quickstart</strong></a> ·
  <a href="#example"><strong>Example</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#contributors"><strong>Contributors</strong></a>.
  <a href="#read-more"><strong>Read More</strong></a>

</p>
<br/>

## How It Works

This project utilizes the [ChatGPT API](https://openai.com/api/) and the [Vercel AI SDK](https://sdk.vercel.ai/docs) with streaming capabilities. Here's a quick overview of the workflow:

1. **User Input**: You input a text prompt or query in a user-friendly form.

2. **Prompt Construction**: The system constructs a query prompt based on the input.

3. **AI Magic**: The prompt is sent to the ChatGPT API using a Vercel Edge Function.

4. **Streamlined Response**: The AI-generated response is streamed back to the application's user interface, allowing you to view and use the generated query effortlessly.

## Quickstart

1. Clone this repository to your local machine.

2. Create an account on [OpenAI](https://beta.openai.com/account/api-keys).

3. Store your API key in a file named `.env` in the project directory.

4. Run the application from the command line, and it will be available at `http://localhost:3000`.

## Example

#### Endpoint

- SWAPI GraphQL Endpoint: https://swapi-graphql.netlify.app/.netlify/functions/index

#### Question

- Retrieve the titles of all films

## Tech Stack

- [Next.js](https://nextjs.org/) – Framework
- [Tailwind](https://tailwindcss.com/) – CSS
- [ChatGPT API](https://openai.com/api/) – API
- [Vercel](https://vercel.com/) – Deployments

## Contributors

<a href="https://github.com/geobde/graphqlexplorer/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=geobde/graphqlexplorer&max=400&columns=20" />
</a>

## Repo Activity

![GraphQL Explorer repo activity – generated by Axiom](https://repobeats.axiom.co/api/embed/c4b64b729cbd70f2500b9badac7fdd825ef48f33.svg "Repobeats analytics image")

## Read More

[Generate GraphQL queries from simple text prompts](https://medium.com/@geobde/generate-graphql-queries-from-simple-text-prompts-d276912d6a60)

## License

See the [LICENSE](./LICENSE) file for licensing information.
