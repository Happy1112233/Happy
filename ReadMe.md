<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SawiSaPagIbig</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SawiSaPagIbig</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Support Ticket</a>
            <a href="#">Chat Groups</a>
            <a href="#">Forums</a>
            <a href="#">Seminars</a>
        </nav>
    </header>

    <main>
        <section class="about">
            <h2>Your partner in resolving relationship issues</h2>
            <p>Welcome to SawiSaPagIbig. We are here to help you with any relationship problems you might be facing. Whether it's misunderstandings, breakups, or other issues, our team is ready to provide you with the advice and support you need.</p>
        </section>

        <section class="support-ticket">
            <h2>Submit a Support Ticket</h2>
            <p>If you need personal advice or support, please submit a support ticket. Our team will respond to you as soon as possible.</p>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="issue">Describe your issue:</label>
                <textarea id="issue" name="issue" rows="4" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>

        <section class="chat-groups">
            <h2>Join Our Chat Groups</h2>
            <p>Connect with others who are going through similar experiences. Join our chat groups to share your story and get advice from peers.</p>
            <button>Join Chat Group</button>
        </section>

        <section class="forums">
            <h2>Forums</h2>
            <p>Participate in our forums to discuss various relationship topics. Ask questions, share your experiences, and learn from others.</p>
            <button>Visit Forums</button>
        </section>

        <section class="seminars">
            <h2>Upcoming Seminars</h2>
            <p>Attend our seminars to learn about relationship problems and solutions. Our experts provide insights and practical advice to help you navigate your relationship issues.</p>
            <button>View Seminar Schedule</button>
        </section>

        <section class="team">
            <h2>Meet Our Team</h2>
            <div class="team-member">
                <p><strong>Marc jm Pontila</strong></p>
                <p>Founder & Relationship Advisor</p>
            </div>
            <div class="team-member">
                <p><strong>Alaiza Antonio</strong></p>
                <p>Relationship Counselor</p>
            </div>
            <div class="team-member">
                <p><strong>Reynard Canen</strong></p>
                <p>Support Specialist</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 SawiSaPagIbig. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #e91e63;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

nav a {
    margin: 0 1em;
    text-decoration: none;
    color: #fff;
}

main {
    padding: 2em;
    background-color: #f4f4f4;
}

section {
    margin-bottom: 2em;
    background-color: #fff;
    border-radius: 10px;
    padding: 1em;
}

button {
    background-color: #e91e63;
    color: #fff;
    border: none;
    border-radius: 5px;
    padding: 0.5em 1em;
    cursor: pointer;
}

button:hover {
    background-color: #d81b60;
}

.team-member {
    margin: 1em 0;
}

footer {
    text-align: center;
    padding: 1em;
    background-color: #e91e63;
    color: #fff;
}

