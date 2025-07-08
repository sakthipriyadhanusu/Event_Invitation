# Event_Invitation

## DATE: 08.07.2025

## Objective:
To design a visually appealing event invitation using HTML elements and basic CSS styling for structure and layout.

## Tasks:
1. Set Up the HTML Document
Use <!DOCTYPE html>, <html>, <head>, <title>, and <body>.

Set the title as "Event Invitation".

➤ CSS Styling:

Set background color for the body (e.g., light beige or pastel).

Apply font-family (e.g., sans-serif) for consistent typography.

2. Create the Invitation Container
Use a <div> with a class like invite-card to wrap the entire content.

➤ CSS Styling:

Set width, padding, border-radius, and a soft box-shadow.

Center the card using margin: auto and margin-top.



## HTML code:

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Event Invitation</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="invite-card">
    <h1>Annual Cultural Fest</h1>
    <h3>Celebrate Talent & Traditions</h3>

    <img src="k.jpg" alt="Cultural Fest Banner">

    <p><span>Date:</span> September 15, 2025</p>
    <p><span>Time:</span> 5:30 PM onwards</p>
    <p><span>Venue:</span> College Open Grounds</p>

    <footer>
      <p>RSVP: Sakthi Priya D</p>
      <p>Contact: +91-9876543210 | sakthi@gmail.com</p>
    </footer>
  </div>

</body>
</html>


```

style.css
```
/* Body styling */
body {
  background-color: #acb0f6; /* pastel light */
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 40px 20px;
}

/* Invitation card container */
.invite-card {
  max-width: 500px;
  background: #bbea5e;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
  margin: 50px auto;
  text-align: center;
}

/* Event title */
.invite-card h1 {
  font-size: 2em;
  color: #100b1c; /* purple theme */
  margin-bottom: 10px;
}

/* Subtitle */
.invite-card h3 {
  font-size: 1.2em;
  color: #ea8108; /* darker purple */
  margin-bottom: 30px;
}

/* Event details */
.invite-card p {
  font-size: 1em;
  color: #333;
  margin: 10px 0;
}

.invite-card span {
  font-weight: bold;
}

/* Optional image/banner */
.invite-card img {
  max-width: 100%;
  border-radius: 10px;
  margin: 20px 0;
}

/* RSVP footer */
footer {
  margin-top: 30px;
  padding-top: 15px;
  border-top: 1px solid #ddd;
  font-size: 0.9em;
  color: #555;
}
```
## OUTPUT
![Screenshot 2025-07-08 221135](https://github.com/user-attachments/assets/80f18929-f23b-4fe4-8545-5a6d0bf10dce)


## Result
 A visually appealing event invitation using HTML elements and basic CSS styling for structure and layout is thus designed.
