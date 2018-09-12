1. a = document.querySelector(".profile-image") - select profile image

a.setAttribute("src", "https://placebear.com/200/300") - change image

2. a = document.querySelector("#left-image img") - seleect image from image ID

a.setAttribute("src", "https://upload.wikimedia.org/wikipedia/en/thumb/e/e0/Steve_Urkel.jpg/220px-Steve_Urkel.jpg") - insert Steve_Urkel

3. a = document.querySelector(".bio-info-value.bio-info-name")

a.textContent = 'Bill'

4. a = document.querySelector("#employment .info-title") - select h3

a.textContent = 'Unemployment' - change text content

5. b = document.querySelector("body")

b.style.backgroundColor = "purple"

6. h = document.querySelectorAll(".highlight")

h.forEach(function(highlight) {highlight.style.backgroundColor = "yellow";});

7. f = document.querySelector("h1")

f.style.fontFamily = 'monospace'

8. dic = document.querySelectorAll("a.action-icon-bg")

for(var i = 0; i < dic.length; i++) {dic[i].style.backgroundColor = 'pink';}
"pink"

9. p = document.querySelector("#name")

p.placeholder = 'identify yourself'

10. msg = document.querySelector("#message")

msg.placeholder = "state your business"

11. nemesis = document.querySelector("#name)

nemesis.setAttribute('value', 'your nemesis')

12. koala = document.querySelector("#email")

koala.setAttribute('value', 'koalathebear@gmail.com')

13. submit = document.querySelector("#submit")

submit.setAttribute('value', 'en garde!')

14. document.querySelector("#submit").setAttribute('disabled', true)

15. 
values = document.querySelectorAll(".bio-info-value")

values.forEach(function(value) {
    value.textContent = ""
})
