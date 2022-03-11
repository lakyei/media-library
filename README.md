# Build a Library
## Using classes to organize the content of a media library

Congratulations, you’ve become head librarian at your local Books-‘N-Stuff, which is in dire need of your help. They’re still using index cards to organize their content! Yikes.

But no worries, you know some JavaScript, so let’s get to work modernizing your new digs.

Books-‘N-Stuff carries three different types of media: books, CDs, and movies. In this project you will create a parent class named `Media` with three subclasses: `Book`, `Movie`, and `CD`. These three subclasses have the following properties and methods:

### 1. Book
  - **Properties:** `author` (string), `title` (string), `pages` (number), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty).
  - **Getters:** all properties have a getter
  - **Methods:** `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`

### 2. Movie
  - **Properties:** `director` (string), `title` (string), `runTime` (number), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty)
  - **Getters:** all properties have a getter
  - **Methods:** `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`
### 3. CD
  - **Properties:** `artist` (string), `title` (string), `isCheckedOut` (boolean, initially `false`), and `ratings` (array, initially empty), `songs` (array of strings)
  - **Getters:** all properties have a getter
  - **Methods:** `.getAverageRating()`, `.toggleCheckOutStatus()`, and `.addRating()`
