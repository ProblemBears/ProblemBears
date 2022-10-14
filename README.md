<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap');

    * {
        font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
    }

    .grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 20% 15% 32.5% 32.5%;
        grid-template-areas:    "header header"
                                "title title"
					            "desc gif"		  
					            "links gif";
    }

    .header {
        display: inline-block;
        grid-area: header;
        justify-self: center;
        align-self: center;
    }

    .titles {
        grid-area: title;
        justify-self: center;
        align-self: start;
        padding: 5px 10px;
        color: #e8e6e3;
        display: inline-block;
        background-color: #208637;
        border-radius: 10px;
    }

    .description {
        grid-area: desc;
        display: inline-block;
        text-align: center;
        overflow: scroll;
    }

    .links {
        grid-area: links;
        display: inline-block;
        justify-self: center;
        align-self: start;
    }
    
    li {
        text-decoration: none;
        display: inline-block;
        text-align: center;
    }

    .link {
        all: unset
        text-decoration: none;
        color: #e67e24;
    }

    .gif {
        grid-area: gif;
        display: inline-block;
        text-align: center;
    }

    img {
        border-radius: 5rem;
    }
</style>

<div class="grid">

<h1 class="header"> 🐻 Jonathan Martinez 🐻 </h1> 
<div class="titles">Software Engineer | 3D Generalist </div>

<p class="description" >
Hi there 👋 Welcome to my Github!
I'm a Software Engineer and self-taught 3D Generalist, interested in game development. I mainly work with C++, Java, and Python, but have also done full-stack web development using the MERN stack. I am a Stony Brook University alumni with a Bachelor of Science in Computer Science. I love animating, tinkering with electronics, playing guitar, and games!
</p>

<div class="gif">
<img src="./images/3DArt.gif"/>
</div>

<div class="links">
    <ul>
    <li> <a style="text-decoration: none;" class="link" href="https://www.problembear.com/"> My Portfolio </a> </li>
    </ul>
</div>

</div>
<!--
**ProblemBears/ProblemBears** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
