# 4K Quality

A customized English, light-theme version of [webp-crusher](https://github.com/shufflethis/webp-crusher), an open-source, browser-based bulk WebP image compressor.

## Features

- Add up to 50 images at a time.
- Compress images to WebP in the browser.
- Set a target output size in KB and a maximum image width.
- View original and compressed file sizes and estimated savings.
- Download processed images together as a ZIP file.
- Images are processed locally in the browser and are not uploaded to a server.

## Deploy on Vercel

1. Import `mukz3467/4k-quality` from GitHub in Vercel.
2. Framework preset: **Other**.
3. Build command: leave empty.
4. Output directory: `.` (project root).
5. Deploy.

No build step, backend, environment variables, or paid API key is required.

## Attribution and license

This project is adapted from [shufflethis/webp-crusher](https://github.com/shufflethis/webp-crusher). The upstream project is distributed under the MIT License; see [LICENSE](./LICENSE). The upstream attribution is also shown in the website footer.

## Notes

- Compression is performed with the browser Canvas API; output depends on browser support and source image.
- The app loads JSZip from a CDN to create the ZIP download.
- Large batches may be memory-intensive on low-RAM phones.
