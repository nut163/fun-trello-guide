# 🃏 Cards 🃏

Cards are the fundamental units of Trello. They represent tasks, ideas, or items within your lists. Let's dive into the world of cards! 🏊‍♀️

## Creating a Card 📝

Creating a card is as simple as clicking the "+ Add another card" button at the bottom of any list. You can give it a name and press "Enter" to create it. Easy peasy! 🍋

```javascript
// Example: Creating a card
let newCard = {
  name: "My First Card",
  list: "To Do"
};
trelloFeatures.createCard(newCard);
```

## Card Details 📋

Cards can hold a lot of information. You can add a detailed description, set a due date, attach files, and much more. To access these options, simply click on the card.

```javascript
// Example: Adding details to a card
let cardDetails = {
  description: "This is a detailed description of my task.",
  dueDate: "2022-12-31",
  attachments: ["file1.pdf", "image.png"]
};
trelloFeatures.updateCard("My First Card", cardDetails);
```

## Comments and Mentions 💬

You can leave comments on a card to provide updates or start a discussion. You can also mention other Trello users to notify them. Just type "@" followed by their username.

```javascript
// Example: Adding a comment with a mention
let comment = {
  text: "Hey @username, check this out!",
  card: "My First Card"
};
trelloFeatures.addComment(comment);
```

## Labels and Checklists 🏷️✅

Assign labels of different colors to your cards to categorize or prioritize them. You can also create checklists within cards to break down tasks into smaller subtasks.

```javascript
// Example: Adding a label and a checklist to a card
let label = {
  color: "green",
  card: "My First Card"
};
let checklist = {
  items: ["Subtask 1", "Subtask 2"],
  card: "My First Card"
};
trelloFeatures.addLabel(label);
trelloFeatures.addChecklist(checklist);
```

That's it for cards! Remember, cards are your friends. They're here to make your life easier, not harder. So have fun with them! 🎉