# Bc. Adam Veselý
**`VUT FIT student`**  

I am currently a student of VUT FIT in Brno, Czechia. I am studying in the IT sphere. Here I publish my school and individual projects.
### About me
```C
#include <aboutme.h>
#include <stdbool.h>

#define HOBBIES 5 // number of mentioned hobbies
#define L_T_COUNT 12 // number of mentioned programming languages and tools I have experience in

int main(void) {
  char *name = "Adam Veselý";                   // Hello! My name is Adam Veselý.
  int age = 23;                                 // I am 23 years old as of now.
  char *birthdate = "03.03.2003";               // I was born on the 3rd of March in 2003.
  char *sex = "Male";                           // I am a male.
  char *curr_school = "VUT FIT";                // I am currently studying at VUT FIT in Brno, Czech Republic.

  char *hobbies[HOBBIES] = {"Hockey",           // My hobbies include playing Hockey,
  "Programming", "Traveling",                   // programming, traveling,
  "Sports", "Learning"};                        // other sports, learning and many more.

  char *experience = "6+ years";                // I've been programming for over 6 years now.
  bool completed_competition = true;            // I've participated in multiple programming competitions, \
                                                   all in which I have placed in the top 10% of participants.
  char *languages_tools[L_T_COUNT] =
{                                               // I have experience with a variety of programming languages and tools, such as,
  "C", "C++", "C#",                             // C, C++, C#,
  "Python", "Git", "Svelte"                     // Python, Git, Svelte,
  "REST", "Typescript", "Node.js",              // HTML, Typescript, Node.js,
  "Rust", "SQL", "x86-64 Assembly"              // Rust, SQL, x86-64 Assembly, and more.
};                                              // These are the tools and programming languages I am most proficient in.

  return EXIT_SUCCESS;
}
```
<details>
<summary><h3>Easier to read</h3></summary>
  <ul>
    <li>Hello! My name is Adam Veselý.</li>
    <li>I am 23 years old as of now.</li>
    <li>I was born on the 3rd of March in 2003.</li>
    <li>I am a male.</li>
    <li>I am currently studying at VUT FIT in Brno, Czech Republic.</li>
    <li>My hobbies include playing Hockey, programming, traveling, other sports, learning and many more.</li>
    <li>I've been programming for over 6 years now.</li>
    <li>I've participated in multiple programming competitions, all in which I have placed in the top 10% of participants.</li>
    <li>I have experience with a variety of programming languages and tools, such as:</li>
      <ul>
        <li>C, C++, C#,</li>
        <li>Python, Git, Svelte,</li>
        <li>REST, Typescript, Node.js,</li>
        <li>Rust, SQL,  x86-64 Assembly and more.</li>
        <li>These are the tools and programming languages I am most proficient in.</li>
      </ul>
  </ul>
</details>
