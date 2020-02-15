1. First Name, Last Name (real ones) Daniil Chsherbina
2. Contact Info (add several ways to contact you) email: preeno88@gmail.com, number: +77001216804;
3. Summary (your goal, wishes, reveal what is important for you, what do you want and why.
Some kind of self-presentation. In case of lack of experience  Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace . Rather being a Junior means always
learning new things from everywhere etc.).
I want to gain experience, learn js, start learning ReactJS, communicate more with knowledgeable people and gain skills from them.
4. Skills (e.g. programming languages, frameworks, methodologies, version control, tools etc.) HTML5, CSS3, LESS, PHP, JS(beginner), WordPress.
5. Code examples (LATEST)
var chatContainer = document.querySelector('.chat-content');
var messages = chatContainer.children;
var newMessageForm = document.querySelector('.chat-form');
var newMessageInput = newMessageForm.querySelector('.chat-form-input');
var messageTemplate = document.querySelector('#message-template').content;
var newMessageTemplate = messageTemplate.querySelector('.chat-message');

newMessageForm.addEventListener('submit', function (evt) {
  evt.preventDefault();

  var messageText = newMessageInput.value;
  var newMessage = newMessageTemplate.cloneNode(true);
  newMessage.children[1].textContent = messageText;
  chatContainer.appendChild(newMessage);
  deleteMessageHandler(newMessage);
  newMessageInput.value = '';
});
var deleteMessageHandler = function (message) {
  var crossSign = message.querySelector('.chat-message-button');
  crossSign.addEventListener('click', function () {
  message.remove(); 
  });    
}
for (var i = 0;i < messages.length;i++) {
  deleteMessageHandler(messages[i]);  
}

6. Experience (for a Junior Dev it means all kinds of experience: coding tests, projects from courses,
freelance projects - wherever they had the opportunity to demonstrate skills they have.
Also it would be awesome if you add links to source code)
http://l70012sx.beget.tech
http://s70262f1.beget.tech

7. Education (including courses, seminars, lectures, online learning) HTMLAcademy, SkillBox;
8. English (elaborate on what kind of practice you had, if any, how long it lasted and so on) 
I used English to communicate with people in computer games, went to courses for 6 months.
