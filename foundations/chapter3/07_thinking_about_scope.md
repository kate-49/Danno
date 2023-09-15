# Thinking about scope and testing

It's great that we have been writing code that passes pre-written tests. This is part of a style of coding called `Test Driven Development` or `TDD`, which will be a big part of the next module.

Before we get there, here is something to consider.

## Challenge

One of the drills you were asked to complete in the challenges for this chapter was for a `Basket` class. We needed to be able to add items to a basket and list the items in the basket. The following code passes all the tests. Copy it into the file where you wrote your own code and run the tests again. But there is something wrong with the code which the tests don't cover. 

```ruby
class Basket
  def initialize
    @@items = []
  end

  def add(item)
    @@items << item
  end

  def items
    return @@items
  end
end
```

Compare the above to your own code, but try to focus on behaviour rather than notation -- there is always more than one way to code a feature. Think about what a class is, how it is used. Maybe copy the above into the IRB `repl` and play about with it by making instances of the class.

As a final clue: consider the questions you were asked to comment on at the [end of chapter 2](../chapter2/06_chapter_2_review.md)

<!-- OMITTED -->


[Log your progress and go to the next challenge](https://makers-event-logger.herokuapp.com/?event=07_thinking_about_scope.md&repository=makersacademy%2Fruby_foundations&redirect=chapter3%2F08_chapter_3_review.md)

<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fruby_foundations&prefill_File=chapter3%2F07_thinking_about_scope.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fruby_foundations&prefill_File=chapter3%2F07_thinking_about_scope.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fruby_foundations&prefill_File=chapter3%2F07_thinking_about_scope.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fruby_foundations&prefill_File=chapter3%2F07_thinking_about_scope.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fruby_foundations&prefill_File=chapter3%2F07_thinking_about_scope.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->
