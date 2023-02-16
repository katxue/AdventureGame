# AdventureGame
Problem statement
The local middle school would like some text adventure games to keep their students occupied
during down time. The school is leaving it up to your skill and good judgement to develop a
game. It is up to you what the story and theme is but there are some requirements:
• In your adventure game, there must be at least two paths, with each has a depth of 3 (an if
with a nested if that has a nested if) to complete the adventure, and there needs to be at least 2
options with each decision. Example below:
if (first_input == 1) {
…
if (second_input > third_input) {
…
if (fourth_input != fifth_input) {
…
}
else {
…
}
}
else if (second_input <= third_input) {
…
}
}
else if (first_input == 2) {
…
if (second_input > third_input) {
…
if (fourth_input != fifth_input) {
…
}
else {
…
}
}
else if (second_input <= third_input) {
…
}
}
• During your adventure game, you must get at least 5 user inputs for every path. Create
variables to store them.
• There must be
