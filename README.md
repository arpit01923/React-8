# Fruit Interpreter

## List of Contents

- Descritpion
- Input
- Processing
- Output
- Link

> **Description:** Want to know what an fruit mean then click on an fruit and know it's meaning. One can also search an fruit meaning, if in database else user will get to know.

<br>

> **Input:** A user can give input in two ways one by entering an fruit in input section and second by clicking on icons in display section. In input section user has to enter fruit to check it's meaning.

<br>

> **Output:** User will get to know fruit meaning if available in database after clicking on fruit display section, if user enters an fruit which is not available then user is informed with message `we don't have this in our database` else with meaning of fruit. Output is text message for the user.

<br>

> **Processing:**

- User has to click on fruit or enter an fruit to know fruit meaning.
- If user click on fruit, then after that function `emojiClickHandler` is called, which fruit akes as input argument of `event type` and then searches for fruit meaning in database and display it to the user in output section. For this `emojiClickHandler` function uses `useState` function()(`setEmojiMeaning`) to get display emoji meaning to the user.
- If user enters an emoji then using function `onChange` emoji meaning is checked in the database if found then appropriate meaning is displayed to the user, else `we don't have this in our database` message. For this function `onChange` uses function `emojiClickHandler` input argument of `string type` and then similarly uses function `useState` to update the user.

<br>

> **Link:** [Fruit Interpreter](codesandbox.io/s/github/arpit-dotcom/react-8)
