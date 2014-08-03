# Focus On This

I get distracted a lot. The Internet is an enabler for me, I open Safari or Chrome to do something and 3 hours later I've been down a hundred paths and if I'm lucky some of those were tangentially related to what I set out to do in the first place.

There are a number of tricks I use to stay focused, like taking notes, writing down next steps for everything, and then always referring back to those notes. Only keeping a couple apps open at once. Not opening hackernews or any news site for that matter. Only opening my Twitter or email client a few times a day.

Today I decided to take things a step further. The screen I see most often on my computer is the new tab screen in Safari and Chrome, so I put the thing I should be focused on front and center.

![open a new tab in safari](http://cl.ly/image/1a2C1j3y1h05/safari-focus-on-this.gif)

## Installation

Clone this repository to your local machine. Example:

```bash
$ cd ~/Sites
$ clone https://github.com/jonmagic/focus-on-this.git
```

Now create a symlink to the `focus` executable in a directory that is a part of your path.

```bash
$ ln -s /path/to/focus-on-this/focus /usr/local/bin/focus
```

Next I set my home page in Safari to be `file:///path/to/focus-on-this/this.html` (replace the path/to with the appropriate path).

For Chrome I set the homepage and then had to install the [Replace New Tab Page](https://chrome.google.com/webstore/detail/replace-new-tab-page/cnkhddihkmmiiclaipbaaelfojkmlkja) extension and then configure it to open new tabs to `file:///path/to/focus-on-this/this.html`.

## Usage

You can update your focus by using the `focus on` command or by editing the html page directly.

```bash
$ focus on Getting flowers for our anniversary.
```

You can see your current focus in the browser of course or by running the focus command by itself.

```bash
$ focus
Focus On Getting flowers for our anniversary.
```

### Contributors

* [@jonmagic](https://github.com/jonmagic)

## License

See [LICENSE](LICENSE).
