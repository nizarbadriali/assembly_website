# ECE 5 Lab 4 – Robot Assembly

Robot building and assembly website for our ECE 5 (UC San Diego) Lab 4 line-following robot.

**Team 69 – CANT:** Kevin Nguyen · Kevin Chrikjian · Tanzim Rahman · Nizar Ali

## Editing the site

- All content is in `index.html`.
- Put photos in `images/` using these filenames (or change the `src` in `index.html`):

| File | Section |
|---|---|
| `images/build-potentiometers.jpg` | Build – 1A Potentiometers |
| `images/build-photoresistors.jpg` | Build – 1B Photoresistors |
| `images/build-motors.jpg` | Build – 1C Motor driver & ESP32 |
| `images/build-cad.png` | Build – 1D CAD screenshot |
| `images/assembly-1.jpg`, `images/assembly-2.jpg` | Assembly |


## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Publishing (GitHub Pages)

1. Push to `main`.
2. On GitHub, go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**,
   then pick branch `main` and folder `/ (root)`.
3. The site will be live at `https://nizarbadriali.github.io/assembly_website/`.
4. The repo must be **public** so anyone can open the link. Test it in a private/incognito window.
