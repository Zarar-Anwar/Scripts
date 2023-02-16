# Scripts
Here are some scripts

#Whatsapp Messages Loop

My this Script only work in laptop very soon will provide another to work in Phones.

#Step 1
Open Whatsapp at Browser
#Step 2
Select Contact and Type Message 
#Step 3
Press Ctrl+Shift+i Or Right Click at Mouse on chatBox and Inspect it
#Step 4
Copy Code and paste in console and hit Enter
 
var message =" ";
var counter = parseInt(prompt("How many Times ?", 10));
window.InputEvent = window.Event || window.InputEvent;
var event = new InputEvent("input", { bubbles: true });
var textbox = document.getElementsByClassName("selectable-text copyable-text")[1];
for (let index = 0; index < counter; index++) {
  textbox.innerHTML = message;
  textbox.dispatchEvent(event);
  document.getElementsByClassName("tvf2evcx oq44ahr5 lb5m6g5c svlsagor p2rjqpw5 epia9gcq")[0].click();
}

Script Made by zZaala.
