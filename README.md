# NoMaD Workshop

Telegram and Discord content tools, built by NoMaD. Everything runs in your browser and your files are never uploaded.

**Open the app:** https://nomad-wolf-clan.github.io/Workshop/

No install, no account, no uploads. Open the link on a computer or phone and start creating.

## One project, every tool
Open a video or image once. BGRemover, Upscale, GIF maker and Editor all edit the same file live, in any order, with no downloading and re-uploading in between. The project bar above the video shows every active edit. Tap a chip to jump to that tool, or ✕ to switch an edit off. Every export includes all of your edits.

## Tools

**BGRemover:** remove a solid-color background from the project.
- Pick the exact background color with the eyedropper, or let the app detect it
- Tune Tolerance, Softness, Choke, Despill and Shadows, and check edges in Split or Matte view
- Switch background removal on or off for the whole project at any time
- **Stroke:** add an outline around the cut-out subject. Choose its size, color and opacity. It's drawn before the crop, so cropping or changing the aspect ratio cuts straight through it for artistic sticker borders

**Upscale:** enlarge the project 2× or 4× with sharp resize (or Off).
- Split view compares the result against a plain resize, and 100% zoom shows real pixels
- Images up to 8192 px, video up to 4096 px

**GIF maker:** turn the project into a GIF.
- Resolution, frame rate, speed, colors and a target file size
- Transparent when the background is removed, or on a background color you choose

**Editor:** shape the project.
- Add more videos or images to the end of the timeline (images play as stills, 3 s by default, any length you set)
- Split the timeline at the playhead into segments, delete the parts you don't want, and undo any change
- Duplicate a segment to repeat it, or reverse it to play backwards (sound reversed too)
- Set the speed of each segment (0.25× to 4×), with pitch-preserved audio
- Frame crop by dragging a box, with Free, 9:16, 1:1, 4:5 or 16:9 locks
- Change the aspect ratio (9:16, 1:1, 4:5, 16:9, 4:3) with bars, blurred background or fill
- Timed captions you type, burned into the video (size and position)

## Export (from any tool)
- **Short-form MP4:** 1080×1920 (9:16), H.264 16–24 Mbps, AAC 192k, for TikTok, Reels and Shorts
- **Long-form MP4:** 1920×1080 (16:9), H.264 16–24 Mbps, AAC 192k, for YouTube
- **Telegram video sticker:** 512 px, ≤3 s, ≤30 fps, ≤256 KB, VP9 with transparency, no audio
- **Telegram custom emoji:** 100×100, 64 KB by default, 256 KB optional
- **Discord emoji:** animated GIF or static PNG, 128×128, ≤256 KB
- **Discord sticker:** animated APNG (smooth transparent edges) or GIF, or static PNG, 320×320, ≤512 KB
- Static Discord files from a video use the frame at the playhead
- **WebM:** full quality, transparent when the background is removed
- **GIF:** resolution, frame rate, size target, background color
- **Images:** PNG, Telegram static sticker (512 px), Telegram static emoji (100×100), Discord emoji (PNG 128×128), Discord sticker (PNG 320×320)
- Export several formats at once, then download each or all as a zip

Projects longer than 3 s are sped up to fit (or trimmed) for Telegram, cropped to your subject, and sized to stay under Telegram's limits.

Discord files are square, cropped to your subject and kept under Discord's size limits. Frame rate, colors and motion detail are lowered only as far as needed. For long projects, set Length to 3 s.

## Editor shortcuts
- **S** split at the playhead · **D** duplicate · **R** reverse · **Delete** remove the selected segment · **Ctrl+Z** undo

## How to use
1. **Open** a video (MP4, WebM) or image (PNG, JPG, WebP).
2. Use any tools, in any order. The preview always shows the full result.
3. Click **Export**, tick the formats you want, and download your files.

## On your phone
- Upright: a square video window stays pinned under the header, and every setting scrolls freely below it. The tool tabs sit in a bar at the bottom.
- Sideways: the square video window stays on the left, and the tabs and settings scroll on the right. It switches automatically when you turn the phone.
- Pick the output shape (9:16, 1:1, 4:5, 16:9, 4:3) in the Editor's Aspect ratio setting. The video window always stays square.

## Good to know
- Works best in Chrome or Edge on desktop or Android.
- iPhone and iPad (Safari): loading, background removal, GIF maker and image tools work. Video exports need iOS 16.4 or later, and some formats may not be available.
- MP4 can't be transparent. With the background removed, MP4 exports use the Editor's bar color behind the subject.
- Telegram turns GIFs into silent MP4s and drops transparency. For transparent Telegram content, use the sticker or emoji exports.
- GIF transparency is on or off per pixel, so Discord GIFs blend their edges into the theme you pick (dark by default). APNG stickers keep soft edges on any theme.
- Added clips keep the first clip's frame size. Clips with a different shape are fitted inside it with transparent edges.
- Videos recorded on iPhone are often HEVC and may not open in Chrome on a computer. Convert them to H.264 MP4 first.

---
Built by NoMaD.
