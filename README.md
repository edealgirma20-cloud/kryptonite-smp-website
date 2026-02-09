# kryptonite-smp-website
Website for Kryptonite SMP Minecraft Server
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krytonite SMP</title>
    <style>
        body {
            background-color: #1c1c1c;
            color: #00ff00;
            font-family: Arial, sans-serif;
        }
        h1, h2, h3 {
            text-align: center;
        }
        .section {
            margin: 20px;
            padding: 10px;
            border: 1px solid #00ff00;
            border-radius: 5px;
            background-color: #2a2a2a;
        }
        a {
            color: #00ff00;
            text-decoration: none;
        }
        footer {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Krytonite SMP</h1>
    </header>
    <section class="section">
        <h2>Server Information</h2>
        <p>IP Address: <strong>Krytonite-SMP.eagler.host</strong></p>
    </section>
    <section class="section">
        <h2>Rules</h2>
        <ul>
            <li>Respect all players.</li>
            <li>No cheating or exploiting bugs.</li>
            <li>Keep chat respectful and friendly.</li>
        </ul>
    </section>
    <section class="section">
        <h2>Staff</h2>
        <ul>
            <li>Admin: Player1</li>
            <li>Moderator: Player2</li>
        </ul>
    </section>
    <section class="section">
        <h2>Join our Discord</h2>
        <p><a href="https://discord.gg/yourdiscordlink">Join our Discord Server</a></p>
    </section>
    <section class="section">
        <h2>Ranks</h2>
        <ul>
            <li>Member</li>
            <li>VIP</li>
            <li>Admin</li>
        </ul>
    </section>
    <section class="section">
        <h2>Shop</h2>
        <p><a href="https://yourshoplink.com">Visit our Shop</a></p>
    </section>
    <footer>
        <p>&copy; 2026 Krytonite SMP</p>
    </footer>
</body>
</html>
.dark-theme {
    background-color: #121212; /* Dark background */
    color: #E0E0E0; /* Light gray text for contrast */
}

.dark-theme a {
    color: #00FF00; /* Green accent for links */
}

.dark-theme button {
    background-color: #00FF00; /* Green buttons */
    color: #121212; /* Dark text on buttons */
}

.dark-theme input {
    background-color: #1C1C1C; /* Dark input fields */
    color: #E0E0E0; /* Light text in input fields */
    border: 1px solid #00FF00; /* Green border for input fields */
}

.dark-theme header, .dark-theme footer {
    background-color: #1A1A1A; /* Slightly lighter dark for header/footer */
}
// scripts/script.js

// Smooth scrolling navigation
const scrollLinks = document.querySelectorAll('a[href^="#"]');

scrollLinks.forEach(link => {
    link.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href');
        const targetPosition = document.querySelector(targetId).offsetTop;
        window.scrollTo({
            top: targetPosition,
            behavior: 'smooth'
        });
    });
});

// Interactive elements
const buttons = document.querySelectorAll('.interactive-button');

buttons.forEach(button => {
    button.addEventListener('click', () => {
        button.classList.toggle('active');
        // Add additional interactive functionality here
    });
});
