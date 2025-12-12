## Happy Birthday!!!

### Wish someone special happy birthday in a special way.

#### [See it Live](https://faahim.github.io/happy-birthday/)

#### Update: Now you can customize all the texts without modifying the code!

On the birthday of a special friend, I felt like the generic happy birthday text just wasn't gonna cut it for me. So I put together this animated web page at the last minute to wish them Happy Birthday.

I decided to publish it so that you can use it to make the special people in your life feel a bit more of what they truly are: special.
You can create your very own happy-birthday page in a few easy steps:

* Fork the repository
* Open `customize.json` and replace the content with your own
* Turn on GitHub pages for your repository (Settings > Pages)
* Share the URL you get at the above step with your friend

**You do not need to create Pull Request to this main repository to get it running.**

I've created the JSON file (`customize.json`) for easy and quick customizability. It allows you the change all of the texts and the image used on the webpage without modifying the code. However, If you want to customize it further, leave the JSON fields empty and edit the HTML file directly. This is because the content in the JSON file overwrites the HTML.

Please note that I've created this page in a hurry and it comes with no warranty.

Feel free to [get in touch with me](mailto:afiur.fahim@gmail.com) if you need any help with it. You can [find me on Twitter](https://twitter.com/faahim01) as well. :)


## Contributing

I've used plain HTML, CSS and JavaScript with [GSAP](https://greensock.com/gsap) for animations.
If you have any idea to improve it or make it more interesting, feel free to send a PR, or create an issue for a feature request.

Happy wishing! 🎉
 
---

## Background music

You can optionally add background music that plays while the animation runs. To enable it:

1. Create a new folder named `audio/` at the project root.
2. Place an MP3 file in that folder and name it `song.mp3` (so the path is `audio/song.mp3`).
3. Open the page in a browser and click the play button in the top-right header (or tap anywhere) to start the music — browsers require a user gesture to start audio.

If no audio file is found the play button will be disabled and the page will still work normally.

Local testing tip (PowerShell):

```powershell
# from project root
python -m http.server 8000
# then open http://localhost:8000 in your browser
```
