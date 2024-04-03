Your Cozy Corner - Login Form 🌙

🎨Project Description:
Here is a beginner-friendly project to create a simple and charming login form.

💻 Technologies:
HTML
CSS

👩‍🍳Process:
I started by creating a header class for my '.header-content', which included a brief overview of the benefits of logging into the website. Next, I placed my login form
in its own div class, allowing me to customize the appearance of its input box, remember/forogt password options, and submit button.

As I shifted my focus to the aesthetics of my CSS, I incorporated a gradient animation to achieve a dynamic background gradient effect and cover. I defined classes such as
'.wrapper' class to style the login form container, featuring a transparent background border and blur effect. Whereas, the '.input-boxes' serve as the container
for input elements, featuring relative positioning and a specific height. Overall, the CSS enhances the login form with a interactive background cover, styled input fields,
and animated elements, resulting in a modern and visually appealing user interface. 

📝 Learned:
🧠 
One lesson I gained was incorporating the gradient-animation feature into my paragraph header. I acheieved this by first defining keyframes as such:
@keyframes gradient-animation{
    0%{
        background-position: 0% 50%;
    }

    50%{
        background-position: 100% 50%;
    }

    100%{
        background-position: 0% 50%;
    }
Then, I ensured to include the command 'background-image: linear-gradient'. Through this process, I found enjoyment in exploring the various aspects of CSS color values.

Embedding icons into my website turned out to be simpler than I anticipated! I learned that to access icons, I first needed to include the following link in my index.html through 'fontawesome.com':
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
Then, wherever I wanted an icon to appear, I added the appropriate HTML tag. For example, to place heart icons alongside my header I did:
<h1><i class="fa-regular fa-heart"></i>Your Cozy Corner <i class="fa-regular fa-heart"></i></h1>


💡Improvement:
- Enable functionality for the login, forgot password, and register buttons when clicked on.
- Include additional interactive elements to captivate users, like a separate prompt for registration if they haven't already signed up.

🚦Running the Project:
Clone the repository to your local machine.
Navigate to the Project Directory.
Open the Project in a Code Editor.
