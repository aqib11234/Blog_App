<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

<h1>Generate Blogs 🤖</h1>

<p>This project is a blog generation application that uses <strong>Streamlit</strong> for the user interface and <strong>LangChain's ChatOllama</strong> model for generating blog content based on user inputs. The application lets users specify a blog topic, desired word count, and a target audience (such as researchers, data scientists, or common readers) to create a customized blog post.</p>

<h2>Features</h2>
<ul>
  <li>Generate blogs on any topic with a specified number of words.</li>
  <li>Select a blog style from available options: Researchers, Data Scientists, or Common People.</li>
  <li>Intuitive user interface powered by Streamlit.</li>
</ul>

<h2>Project Structure</h2>
<ul>
  <li><code>app.py</code>: Main file containing the Streamlit application code.</li>
  <li><code>getLLamaresponse</code> function: Generates a response using the ChatOllama model from LangChain with a customized prompt for blog generation.</li>
</ul>

<h2>Installation</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/aqib11234/Blog_App.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd your-repo</code></pre>
  </li>
  <li>Install the required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the Streamlit application:
    <pre><code>streamlit run app.py</code></pre>
  </li>
</ol>

<h2>Usage</h2>
<ol>
  <li>Open the Streamlit app in your browser after starting the server.</li>
  <li>Enter a blog topic in the input field.</li>
  <li>Specify the number of words for the blog.</li>
  <li>Select the writing style: Researchers, Data Scientist, or Common People.</li>
  <li>Click the <strong>Generate</strong> button to see the generated blog content.</li>
</ol>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Python</strong> - Primary language for development.</li>
  <li><strong>Streamlit</strong> - Used for building the user interface.</li>
  <li><strong>LangChain & ChatOllama</strong> - Used for generating the blog content.</li>
</ul>


<h2>Contributing</h2>
<p>Contributions are welcome! Please open an issue or submit a pull request to improve this project.</p>

<h2>Contact</h2>
<p>For questions or feedback, reach out to <a href="mailto:aqibjamal2002@gmail.com">your-email@example.com</a>.</p>

</body>
</html>
