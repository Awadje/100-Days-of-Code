# 100 Days Of Code - Log

### Day 1: July 14, 2017

**Today's Progress**: Finished two days of 30 days of Javascript. Day 1 I made drumkit where I learned about key events and playing audio. Day 2 I made a JS and CSS Clock where I learned about css animations and Javascript time functions

**Thoughts:** I really like to practice my vanilla Javascript skills and it's awesome to discover the built in functions.

**Link to work:** [30 days of javascript](https://javascript30.com/)


### Day 2: July 15, 2017

**Today's Progress**: Worked on integration tests for my rails blog learned about assert_select to find HTML classes and using sessions in the controller test to test admin functionality. Created a very basic express, mongo, nodeJS API

**Thoughts:** It was new working with rails test instead of Rspec and was great to experiment with it. Did a small API with Express and Mongo amazed by how little actual code was required

**Link to work:** [Blog Repo](https://github.com/Awadje/RailsBlog), [API Repo](https://github.com/Awadje/SimpleAPINodeJS)

### Day 3: July 16, 2017

**Today's Progress**: Played around with  Javascript basics: Variables, Operators, Conditionals, Functions, Objects, Arrays and ES6. Easygoing on Sunday

**Thoughts:** It was good to refresh these basic fundamentals, it's all about repetition.

**Link to work:** [No URL]

### Day 4: July 17, 2017

**Today's Progress**: Learned how to merge json coming from separate models using relations to come together in the React front-end. Wrote functions using filter to match the id's from the data and identify what data belongs where. Used map in combination with the functions to display the data:


```
function getPhotos(photos, id) {
  const filtered = photos.filter(item => item.id === id)

  return {
      uri: filtered[0].attributes.uri
  }
}

photos: item.relationships.photos.data.map(photo_relation => {
            return getPhotos(photos, photo_relation.id)
        }),
```



**Thoughts:** It was new for me to have more than one data object and to merge them correctly. Great learning experience!!

**Link to work:** [No URL]

### Day 5: July 18, 2017

**Today's Progress**: Started with a NodeJS API using Express and Mongoose/MongoDB. Did the basic setup: Server, Controllers, Routes and DB connection

**Thoughts:**  Used to rails, this is all new just soaking it in.

**Link to work:** [API Repo](https://github.com/Awadje/RestaurantAPI)

### Day 6: July 19, 2017

**Today's Progress**: Was onsite at a possible employer and got the assignment to create a search function for a provided NodeJS API. I chose a React/Redux app and got it working within the afternoon.

**Thoughts:** Besides some CORS issues at the beginning the process was quite smooth.

**Link to work:** [No URL]

### Day 7: July 20, 2017

**Today's Progress**: Was onsite at another possible employer with a big Ruby on Rails app(130 models) and got 3 real bugs assigned to me to fix. Signed an NDA so not allowed to talk about it that much.

**Thoughts:** First time in a real codebase so awesome! Also a little milestone to celebrate 1 week into 100days if code!

**Link to work:** [No URL]


### Day 8: July 24, 2017

**Today's Progress**: Was onsite at another possible employer got an assignment to build an app where Admins can create an activity and users(parents) can see and register to those activities and also have to chose which of their children they want to register. It was a Ruby on Rails app and I got up until the part where parents can register to an activity, not able to choose their children yet, however names of the children were already displayed

**Thoughts:** Very nice assignment which seems simple at first hand but gets complex later on.

**Link to work:** [No URL]

### Day 9: July 26, 2017

**Today's Progress**: Continued with my NodeJS/Express Restaurant API

**Thoughts:** Picking up the pace again

**Link to work:** [API Repo](https://github.com/Awadje/RestaurantAPI)

### Day 10: July 27, 2017

**Today's Progress**: Since my feature employer is using VueJS I picked up a course and decided it's going to be the front-end of my Restaurant API. Covered two way data binding (which I think is great) and a lot of basics, computed properties and dynamic styling with CSS.

**Thoughts:** It's all new and am just following along with JSFiddle

**Link to work:** [JS Fiddle Profile](https://jsfiddle.net/user/Awadje/fiddles)

### Day 11: July 29, 2017

**Today's Progress**: Continued with VueJS dove more into dynamic styling without CSS

**Thoughts:** Dynamic styling is great, I can imagine making progress bars and stuff with this :)

**Link to work:** [JS Fiddle Profile](https://jsfiddle.net/Awadje/un28gqcw/4/)
