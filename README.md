

### Installation

To begin, install the required dependencies using the following command:

```bash
npm i
```

# Development Server

After installing the dependencies, run the development server:

```bash
npm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

`cp .env.example .env`

### Configuration

Create a copy of the provided `.env.example` file and name it `.env`. Fill in the required OpenAI API Key in the newly created `.env` file:

```bash
OPENAI_API_KEY=your_api_key
```

Make sure to replace placeholder values with your actual API key.

## Usage

On the index page of your application, locate the input field. Insert your desired subject into the input field, and then click on the `Get Result` button. This action will prompt the framework to generate text based on the provided input.

Additionally, you can switch from text completion to image generation. To do this, click on the toggle to change the mode to "Image" and then click on the `Get Image` button. This will invoke the AI to generate an image based on the input.

The Orcish AI Next.js Framework provides a seamless integration of AI capabilities into your Next.js applications, offering a versatile and user-friendly experience for generating both text and images.

