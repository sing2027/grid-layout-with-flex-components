# Instructions

Fork this repository to start working on the assignment.

Here are the base CSS styles to start with.

```css
body {
  font-family: Arial, Helvetica, sans-serif;
  color: #222;
  text position:center;
}
.emoji {
  border: 1px solid #222;
  border-radius: 8px;
  padding: 1rem;
}

.emoji h2 {
  margin: 0;
  border-bottom: 2px solid #ccc;
}

.emoji a {
  text-decoration: none;
  background-color: #781BAA;
  color: white;
  padding: 1rem;
  border-radius: 8px;
}

.icon {
  font-size: 4rem;
}
body {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 100px;
    justify-content: center;
  }
  
  .emojis {
    display: grid;
    grid-template-columns: 1fr; 
    gap: 20px;
  }
  
  .emoji {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    border: 1px solid #ddd; 
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  
  .emoji * {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 5px;
    border-radius: 5px;
  }
  
  .icon {
    font-size: 48px;
  }
  
  
  h3, .icon, p, a {
    margin: 5px; 
  }
  
  a {
    align-self: flex-end; 
  }
  
  h1 {
    text-align: center; 
    margin-bottom: 20px; 
  }
  
  h2 {
    text-align: center; 
    margin-top: 20px; 
  }
