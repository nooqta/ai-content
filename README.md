
# AI-CONTENT
AI-Content is a AI-Powered Next.js Blog Generator and easy-to-use solution for creating dynamic, high-quality blog content using cutting-edge artificial intelligence technology. This project combines the flexibility and performance of the Next.js framework with advanced language models to provide users with an innovative way to generate blog articles tailored to their specific needs.

## Features:
AI-driven content generation: Leverage the power of advanced language models to create engaging, relevant, and informative blog articles on a wide range of subjects.

- Next.js blog template: A modern, responsive, and SEO-friendly blog template built using the Next.js framework, allowing for fast and scalable content delivery.

- Customizable settings: Adjust various properties like tone, subject, type, and language to tailor the generated content to your specific requirements.

- Predefined or custom content generation: Choose between selling the blog with a set number of AI-generated articles or providing customers with the AI script for generating their own content.

## Usage:
This project is perfect for bloggers, content creators, digital marketers, and businesses looking for an innovative solution to generate high-quality blog content. By harnessing the power of AI and the Next.js framework, users can quickly and easily populate their blogs with engaging, relevant, and informative content, tailored to their unique audience and requirements.

## Getting Started
Follow the steps below to get started with the AI-Powered Next.js Blog Generator:
### Prerequisites:
- Node.js (v12 or higher) installed on your local machine

- pnpm the Fast, disk space efficient package manage

- An OpenAI API key for accessing the language model

- Unsplash API key to generate the cover image

 To use Unsplash for generating cover images for your articles, you'll need to get an API key.

### Step 1: Clone the repository
Clone the AI-Content repository to your local machine by running the following command in your terminal or command prompt:
```
git clone https://github.com/nooqta/ai-content.git
```
### Step 2: Install dependencies
Navigate to the project folder and install the necessary dependencies by running the following commands:
```
cd ai-content
pnpm install
```

### Step 3: Set up the environment
Create a .env file in the project's root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key
UNSPLASH_ACCESS_KEY=your_unsplash_access_key
```
### Step 4: Configure settings

Edit the `settings.json` file in the project folder to customize the properties for generating blog articles, such as the type, length, domain, tone, and language.
Here's a list of properties with brief descriptions for can further customize to fine-tune the content of your article:

1.  **domain** (required): The domain or field of expertise for the generated content, such as "AI," "Environmental Science," or "Healthcare." It helps the AI model generate content that is relevant and accurate to the chosen field.
2. **type** (optional): The type of content you want to generate, such as "Informative," "Persuasive," or "Entertaining." It helps the AI model understand the primary objective of the generated article.
    
3.  **task** (optional): Specifies the writing task, like "Article Writing," "Blog Post Writing," or "Tutorial Writing." It guides the AI model in generating content that aligns with the desired format.
    
4.  **tone** (optional): The tone of voice for the generated content, such as "Neutral," "Formal," "Friendly," or "Passionate." It instructs the AI model on how to convey the information in the article.
    
5.  **length** (optional): Determines the approximate length of the generated content, like "Short," "Medium," or "Long." It assists the AI model in generating articles of the desired size.
6.  **topic** (optional): The specific subject or theme of the generated content. It guides the AI model in generating content that focuses on the chosen topic.
7.  **lang** (optional): The language in which the content should be generated, like "English," "Spanish," or "French." It ensures the AI model generates content in the desired language.
    
8.  **skill** (optional): The skill level of the writer, such as "Beginner," "Intermediate," or "Advanced." It helps the AI model generate content that matches the expected skill level and style.
    
9.  **numArticles** (optional): The number of articles you want to generate. It informs the script how many articles to create using the provided settings.

### Step 5: Generate blog articles
Run the following command in the terminal or command prompt to start generating blog articles using the AI-powered script:
```
npm run generate
```
Remember, only the `domain` property is required. The other properties are optional and can be adjusted to meet your specific requirements.

The generated articles will be saved in the content/posts folder with the article title as the file name and a .mdx extension.

### Step 6: Run the Next.js blog template
To run the Next.js blog template locally, use the following command:
```
npm run dev
```
This will start the development server, and you can view your blog by opening http://localhost:3000 in your web browser.

#### Step 7: Deploy your blog
When you're ready to deploy your blog, follow the official Next.js deployment guide for your preferred hosting platform.

And that's it! You now have a fully functional AI-Powered Next.js Blog Generator. Enjoy creating engaging, high-quality content with the power of artificial intelligence and the flexibility of the Next.js framework.

## Future Features

Here are some exciting features we're planning to add to the project in the future:

1.  **Automated Article Generation**: Implement a Vercel cron job to automate the process of creating articles on a timely basis. This feature will allow you to schedule article generation and automatically publish new content on your blog.
    
2.  **Langchain Integration**: Harness the power of agents, chains, and tools from Langchain to expand the capabilities of the project, such as:
    
    -   Generating drafts for research papers based on reference papers from arXiv.org.
    -   Creating blog posts inspired by Wikipedia articles.
    -   Exploring endless possibilities for generating unique and engaging content.
3.  **Text-to-Speech Audio**: Integrate Elvenlab API to generate text-to-speech audio files for each article, providing an alternative way for users to consume content on your blog. This feature will improve the accessibility of your content and enhance the overall user experience.
    

As the project evolves, we'll continue to explore new ways to make content generation more efficient, engaging, and versatile. Stay tuned for updates!
## Credits

This project was made possible thanks to the invaluable contributions and tools provided by the following:

-   **[Vercel](https://nextjs.org/)**: For providing the wonderful Next.js framework and hosting the project.
-   **[OpenAI](https://openai.com/)**: For their powerful AI models that generate the content.
-   **[Next-ContentLayer](https://github.com/shadcn/next-contentlayer)**: for providing the theme.
-   **[ContentLayer](https://www.contentlayer.dev/)**: For streamlining the process of creating blog articles using .mdx.
-   **[MDX](https://mdxjs.com/)**: For allowing the seamless integration of React components, HTML, and Markdown in a single file.
-   **[Tailwind](https://tailwindcss.com/)**: An utility-first CSS framework that enables rapid building of beautiful and responsive designs.
-   **[Langchain](https://docs.langchain.com/docs/)**: For their support in helping build a project powered by advanced language models.
-   **[llElevenLabs](https://beta.elevenlabs.io/speech-synthesis)**: For simplifying the process generating speech audio from text (TTS)

We would like to express our gratitude to these organizations and projects for their significant contributions to the development and success of this project.

##   Contributing

We welcome contributions from the community to help improve and expand this project. If you're interested in contributing, please refer to the [CONTRIBUTION.md](CONTRIBUTION.md) file for guidelines on how to get started, including information on:

-   Reporting bugs and submitting feature requests
-   Setting up your development environment
-   Submitting pull requests
-   Adhering to the project's coding style and best practices

Together, we can make this project even better and more useful for everyone. Thank you for considering to contribute!

## License

This project is licensed under the MIT License. The MIT License is a permissive free software license, which means you have the freedom to use, modify, distribute, and even sell the software, as long as you provide attribution back to the original author.

For more information on the terms and conditions of the MIT License, please see the [LICENSE](LICENSE) file in the project repository or visit [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT).

##   Sponsoring

If you find this project helpful and would like to support its development and maintenance, please consider becoming a sponsor. Your sponsorship will help us continue to improve the project and add new features, benefiting the entire community.

To become a sponsor, please visit the following link: [https://github.com/sponsors/anis-marrouchi](https://github.com/sponsors/anis-marrouchi)

Your support is greatly appreciated, and it will have a significant impact on the project's future. Thank you for considering to sponsor this project!