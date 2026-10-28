# 4K Quality

A lightweight, responsive image toolkit for resizing images to 4K dimensions, compressing image files, and converting supported images to WebP, JPG, or PNG.

## Features

- Resize images to 4K UHD, portrait 4K, Full HD, square, or custom dimensions.
- Keep the original aspect ratio while resizing.
- Export to WebP, JPG, and PNG with adjustable quality where supported.
- Preview output and download it locally.
- Process images in the browser; selected images are not uploaded to a server.
- Responsive layout for desktop and mobile.

## Deploy on Vercel

1. Import `mukz3467/4k-quality` from GitHub in Vercel.
2. Framework preset: **Other**.
3. Build command: leave empty.
4. Output directory: `.` (project root).
5. Deploy.

No build step, server, environment variables, or paid API key is required.

## Important limitation

The 4K preset resizes an image to 4K pixel dimensions. It does not perform AI super-resolution and cannot recreate details absent from the source image.

## Privacy

Image processing uses browser APIs (Canvas and object URLs). The app does not send image contents to a backend.
