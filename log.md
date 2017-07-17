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

**Today's Progress**: Learned how to merge objects coming from separate models using relations to come together in the React front-end. Wrote functions using filter to match the id's from the data and identify what data belongs where. Used map in combination with the functions to display the data:


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
