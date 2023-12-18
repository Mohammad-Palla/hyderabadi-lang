<h1 align="center">Hyderabadi Lang</h1>

<p align="center">
  <b>Hyderabadi lang is a toy programming language inspired from bhai lang.</b>
</p>
<br>

<h2 align="center">Installation</h2>

```
npm i -g hyderabadilang
```

<h2 align="center">Usage</h2>

<h4 align="left">Create a new file with .baigan extension (eg: hi.baigan)</h4><br/>

<h4 align="left">Edit the file with a text editor.

```
biryani shuru
  bolo yaaro "aayin... baigan";
biryani barkhast

```

<h4 align="left">Run</h4>

```
miyabhaibolte hi.baigan
```

<h4 align="left">Output</h4>

```
aayin... baigan
```

<h2 align="center">Documentation</h2>

<h3 align="center">General</h3>
<p align="center"><code>biryani shuru</code> is the entrypoint for the program and all program must end with <code>biryani barkhast</code>. Anything outside of it will be ignored.</p>

```

This will be ignored

biryani shuru
// Write code here
biryani barkhast

This too
```

<h3 align="center">Variables</h3>
<p align="center">Variables can be declared using <code>dekho yaaro ye hai</code>.</p>

```

biryani shuru
  dekho yaaro ye hai a = 10;
  dekho yaaro ye hai b = "two";
  dekho yaaro ye hai c = 15;
  a = a + 1;
  b = 21;
  c *= 2;
biryani barkhast
```

<h3 align="center">Types</h3>
<p align="center">Numbers and strings are like other languages. Null values can be denoted using <code>nalla. sahi and galat</code> are the boolean values for true and false respectively</p>

```

biryani shuru
  dekho yaaro ye hai a = 10;
  dekho yaaro ye hai b = 10 + (15*20);
  dekho yaaro ye hai c = "two";
  dekho yaaro ye hai d = 'ok';
  dekho yaaro ye hai e = nalla;
  dekho yaaro ye hai f = sahi;
  dekho yaaro ye hai g = galat;
biryani barkhast
```

<h3 align="center">Built-ins</h3>
<p align="center">Use <code>bolo yaaro</code> to print anything to console.</p>

```

biryani shuru
  bolo yaaro "Hello World";
  dekho yaaro ye hai a = 10;
  {
    dekho yaaro ye hai b = 20;
    bolo yaaro a + b;
  }
  bolo yaaro 5, 'ok', nalla , sahi , galat;
biryani barkhast
```

<h3 align="center">Conditionals</h3>
<p align="center">Hyderabadilang supports simple if else construct , <code>agar patthe</code> block will execute if condition is <code>sahi</code> and <code>sub hath diye to</code> block will execute if condition is <code>galat</code>.</p>

```

biryani shuru
  dekho yaaro ye hai a = 10;
  agar patthe (a < 25) {
   bolo yaaro "a is less than 25";
  } sub hath diye to {
   bolo yaaro "a is greater than or equal to 25";
  }
biryani barkhast
```

<h3 align="center">Loops</h3>
<p align="center">Statements inside <code>jab tak ye hai</code> blocks are executed as long as a specified condition evaluates to sahi. If the condition becomes <code>galat</code>, statement within the loop stops executing and control passes to the statement following the loop. Use <code>bas karo baigan</code> to break the loop and <code className="language-cpp">agla dekho baigan</code> to continue within loop.</p>

```

biryani shuru
  dekho yaaro ye hai a = 0;
  jab tak ye hai (a < 10) {
   a += 1;
   agar patthe (a == 5) {
    bolo yaaro "andar se bolo yaaro ", a;
    agla dekho baigan;
   }
   agar patthe (a == 6) {
    bas karo baigan;
   }
   bolo yaaro a;
  }
  bolo yaaro "done";
biryani barkhast
```

## Contributing
I welcome contributions to improve the Auto-PaLM program. Please feel free to submit suggestions and issues to discuss potential improvements or report bugs, and even help me understand terms and the correct process of open-source projects.

I'm so excited to see how both AutoPaLM will continue to push the boundaries of what is possible with AI in the future!

If you're interested in contributing to this project, please take a moment to review the following guidelines.

### How to Contribute

1. **Fork the repository:** Click on the "Fork" button at the top right of this repository to create your own copy.

2. **Clone your fork:** Clone your forked repository to your local machine using:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

3. **Create a new branch:** Create a new branch to work on your feature or bug fix using:

    ```bash
    git checkout -b feature/your-feature-name
    ```

    or

    ```bash
    git checkout -b bugfix/your-bug-fix
    ```

4. **Make changes:** Make your changes to the code, documentation, or any other relevant files.

5. **Commit your changes:** Commit your changes with a descriptive commit message:

    ```bash
    git commit -m "Add your descriptive commit message here"
    ```

6. **Push to your branch:** Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

7. **Submit a Pull Request:** Open a Pull Request (PR) from your forked repository to the original repository's branch.

### Guidelines

- Ensure your code follows the project's coding standards.
- Provide clear and concise commit messages.
- Keep the documentation up-to-date if relevant.
- Test your changes thoroughly before submitting a PR.
- Ensure your PR does not introduce breaking changes.

### Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.

Thank you for contributing to our project! 🚀

**For any issues raise an issue in the issues tab**
