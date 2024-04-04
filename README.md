<div align="start">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWJtNHk1eGZwYWdlcW5qNjFpazVkaHltNTdrOXN1YjN3djYxbDBncCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/uWL3Nt5cgwsCecmh24/source.gif"  />
</div>
<h3 >👉 I'm Guilherme Carvalho</h3>
<p>I develop web systems (front-end programmer and UI/UX Designer), I also study systems analysis and development</p>
<br>



<h1>📣 Social media</h1>
<div align="start">
   <a href="https://www.linkedin.com/in/gurieel" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
   <a href="https://github.com/Gurieel" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
   <a href="https://www.behance.net/gurieel" target="_blank"><img src="https://img.shields.io/badge/-Behance-blue?style=for-the-badge&logo=behance&logoColor=white" /></a>
   <a href="www.instagram.com/guriel.exe/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</div>

<script>
        function textEffect() {
            const textElement = document.getElementById('hello-world');
            const originalText = textElement.textContent;
            const characters = ['!', '@', '#', '$', '%', '^', '&', '*', '(', ')', '-', '_', '=', '+', '[', ']', '{', '}', '\\', '|', ';', ':', '"', "'", ',', '<', '>', '.', '/', '?', '`', '~'];

            let newText = '';
            for (let i = 0; i < originalText.length; i++) {
                const randomIndex = Math.floor(Math.random() * characters.length);
                newText += characters[randomIndex];
            }

            textElement.textContent = newText;
            setTimeout(() => {
                textElement.textContent = originalText;
            }, 1000);
        }

        setInterval(textEffect, 10000);
    </script>
