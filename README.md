- 👋 Hi, I’m @azramrajpoot
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
azramrajpoot/azramrajpoot is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Premium Website</title>
    <style>
        /* Your existing styles here... */

        .hidden {
            display: none;
        }
    </style>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            var toggleButton = document.getElementById('toggleButton');
            var hiddenContent = document.getElementById('hiddenContent');

            toggleButton.addEventListener('click', function () {
                hiddenContent.classList.toggle('hidden');
            });
        });
    </script>
</head>

<body>
    <!-- Your existing body content here... -->

    <section>
        <div class="container">
            <div class="box">
                <h2>About Us</h2>
                <p>Your compelling story goes here.</p>
            </div>

            <div class="box">
                <h2>Services</h2>
                <p>Explore our premium services.</p>
            </div>

            <div class="box">
                <h2>Toggle Content</h2>
                <button id="toggleButton">Toggle Content</button>
                <div id="hiddenContent" class="hidden">
                    <p>This content is hidden by default and can be toggled.</p>
                </div>
            </div>

            <!-- Add more sections as needed -->

        </div>
    </section>

    <!-- Your existing footer content here... -->
</body>

</html>
