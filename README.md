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
<p align="center">Bhailang supports simple if else construct , <code>agar patthe</code> block will execute if condition is <code>sahi</code> and <code>sub hath diye to</code> block will execute if condition is <code>galat</code>.</p>

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
