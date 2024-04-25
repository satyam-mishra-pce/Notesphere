# Html code

```html
<div class="card">
  <img
    src="https://images.pexels.com/photos/20370952/pexels-photo-20370952/free-photo-of-a-man-with-glasses-and-a-black-shirt.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
    alt="photo-of-a-man"
  />

  <h3 id="name">Black Modi</h3>
  <p clase="intro">
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Minima optio
    accusamus perspiciatis, velit, eveniet ab consectetur pariatur ut, aut
    laboriosam quidem veritatis molestiae fugit totam tempora porro? Voluptate,
    vel dolorem? Neque officia nostrum ex delectus facilis! Quaerat molestiae
    adipisci, cupiditate quam
  </p>
</div>
```


# Css code 

```css

.card {
  margin: 3rem 3rem;
  height: 30rem;
  width: 20rem;
  background-color: #2c2c54;
  border: 2px solid black;
  border-radius: 2rem;
  overflow: hidden;
}
.card > img {
  width: 20rem;
  height: 20rem;
  border-bottom: 5px solid black;
}
.card > h3 {
  text-align: center;
  font-weight: bolder;
  color: rgb(0, 251, 255);
  text-decoration: underline;
}
.card > P {
  font-size: 0.85rem;
  text-align: left;
  letter-spacing: 0.01rem;
  word-spacing: 0.1rem;
  word-break: keep-all;
  margin: 0.5rem;
}
.card:hover {
  height: 40rem;
  width: 25rem;
}

```