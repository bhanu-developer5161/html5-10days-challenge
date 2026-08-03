# Day 07 - HTML5 Multimedia

## Objective

Learn how to add multimedia content such as audio, video, YouTube videos, and Google Maps to a webpage using HTML5.

---

# What is Multimedia?

Multimedia means using different types of media on a webpage.

Examples:
- Audio
- Video
- Images
- Animations
- YouTube Videos
- Google Maps

HTML5 provides built-in multimedia tags, so no external plugins (like Adobe Flash) are needed.

---

# HTML5 Multimedia Tags

1. <audio>
2. <video>
3. <source>
4. <iframe>

---

# 1. <audio> Tag

## Definition

The <audio> tag is used to play audio files on a webpage.

Example:

```html
<audio controls>
    <source src="audio/song.mp3" type="audio/mpeg">
</audio>
```

## Common Audio Formats

| Format | MIME Type |
|---------|-----------|
| MP3 | audio/mpeg |
| WAV | audio/wav |
| OGG | audio/ogg |

MP3 is the most commonly used format.

---

## Audio Attributes

### controls

Displays the audio player controls.

```html
<audio controls>
```

Shows:
- Play
- Pause
- Volume
- Progress Bar

---

### autoplay

Starts playing automatically after the page loads.

```html
<audio autoplay>
```

Note:
Modern browsers usually block autoplay unless the media is muted.

---

### loop

Repeats the audio after it finishes.

```html
<audio controls loop>
```

---

### muted

Starts the audio without sound.

```html
<audio controls muted>
```

---

### preload

Specifies how much audio should be loaded before playback.

Values:

- none
- metadata
- auto

Example:

```html
<audio preload="metadata">
```

---

# 2. <video> Tag

## Definition

The <video> tag is used to play videos directly in the browser.

Example

```html
<video controls>

<source src="video/movie.mp4" type="video/mp4">

</video>
```

---

## Supported Video Formats

| Format | MIME Type |
|---------|-----------|
| MP4 | video/mp4 |
| WebM | video/webm |
| OGG | video/ogg |

MP4 is recommended because it has the best browser support.

---

## Video Attributes

### controls

Displays video controls.

```html
<video controls>
```

---

### width

Sets the width of the video.

```html
<video width="500">
```

---

### height

Sets the height of the video.

```html
<video height="300">
```

---

### autoplay

Starts the video automatically.

```html
<video autoplay muted>
```

---

### muted

Starts the video without sound.

```html
<video muted>
```

---

### loop

Repeats the video continuously.

```html
<video loop>
```

---

### poster

Displays an image before the video starts.

```html
<video poster="images/poster.jpg">
```

---

# 3. <source> Tag

## Definition

The <source> tag specifies the multimedia file for <audio> or <video>.

Example

```html
<source src="song.mp3" type="audio/mpeg">
```

Example

```html
<source src="movie.mp4" type="video/mp4">
```

Using multiple <source> elements allows the browser to choose the first supported format.

---

# 4. <iframe> Tag

## Definition

The <iframe> tag embeds another webpage or external content inside your webpage.

Common Uses

- YouTube Videos
- Google Maps
- PDF Files
- Other Websites (if embedding is allowed)

Example

```html
<iframe
src="https://www.youtube.com/embed/VIDEO_ID"
width="560"
height="315">
</iframe>
```

---

## Important iframe Attributes

### src

Specifies the URL to display.

---

### width

Sets the iframe width.

---

### height

Sets the iframe height.

---

### title

Provides a description for accessibility.

---

### allowfullscreen

Allows full-screen mode for videos.

---

# Embedding YouTube Videos

Normal YouTube URL

```
https://www.youtube.com/watch?v=49_4UcmCvpM
```

Video ID

```
49_4UcmCvpM
```

Embed URL

```
https://www.youtube.com/embed/49_4UcmCvpM
```

Example

```html
<iframe
width="560"
height="315"
src="https://www.youtube.com/embed/49_4UcmCvpM"
allowfullscreen>
</iframe>
```

---

# Why Doesn't <video> Work with YouTube?

Incorrect

```html
<video>

<source src="https://www.youtube.com/embed/49_4UcmCvpM">

</video>
```

Reason

The <video> tag only accepts actual video files such as:

- .mp4
- .webm
- .ogg

A YouTube URL is a webpage, not a video file.

Therefore:

Use <video> for MP4 files.

Use <iframe> for YouTube videos.

---

# Embedding Google Maps

Example

```html
<iframe
src="https://www.google.com/maps?q=Hyderabad&output=embed"
width="600"
height="450">
</iframe>
```

You can replace Hyderabad with any location.

Example:

Tanuku

Rajahmundry

Visakhapatnam

Delhi

---

# Difference Between Audio, Video and iframe

| Feature | audio | video | iframe |
|---------|-------|-------|--------|
| Plays Audio | Yes | No | No |
| Plays Video | No | Yes | Yes (Embedded) |
| Plays MP3 | Yes | No | No |
| Plays MP4 | No | Yes | No |
| Plays YouTube | No | No | Yes |
| Shows Google Maps | No | No | Yes |

---

# Best Practices

✔ Use MP3 for audio.

✔ Use MP4 for video.

✔ Always provide controls.

✔ Use muted with autoplay.

✔ Use iframe for YouTube.

✔ Use descriptive titles.

✔ Organize media files into folders.

Example

Day-07/

audio/

video/

images/

---

# Folder Structure

```
Day-07/

audio.html

video.html

audio_attributes.html

video_attributes.html

iframe.html

embed.html

multimedia_project.html

notes.md

audio/
sample.mp3

video/
sample.mp4
```

---

# Interview Questions

### Q1. What is Multimedia?

Answer:

Multimedia is the combination of different media such as audio, video, images, and animations on a webpage.

---

### Q2. Which tag plays audio?

Answer:

<audio>

---

### Q3. Which tag plays video?

Answer:

<video>

---

### Q4. Which tag embeds YouTube?

Answer:

<iframe>

---

### Q5. Why can't YouTube videos be played using the <video> tag?

Answer:

Because the <video> tag only plays direct video files (.mp4, .webm, .ogg). YouTube provides webpages, so they must be embedded using <iframe>.

---

### Q6. What does the controls attribute do?

Answer:

Displays Play, Pause, Volume, Progress Bar, and Full-screen controls.

---

### Q7. Why is autoplay often used with muted?

Answer:

Modern browsers usually block autoplay with sound. Muting the media allows autoplay to work in many cases.

---

# Day 07 Summary

Today I learned:

✅ Multimedia in HTML5

✅ Audio

✅ Video

✅ Audio Attributes

✅ Video Attributes

✅ Source Tag

✅ iframe

✅ YouTube Embedding

✅ Google Maps Embedding

✅ Multimedia Project

---

# Learning Outcome

After completing Day 07, I can:

- Add audio to a webpage.
- Add video to a webpage.
- Use multimedia attributes.
- Embed YouTube videos.
- Embed Google Maps.
- Understand when to use <video> and when to use <iframe>.