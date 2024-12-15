# VideotoAscii
A rust program to convert a video into ascii characters

My first real rust program 

## Usage

### For windows
1. Download `video-converter.zip`
2. Extract the zip file
3. Run `video-converter --path "path-to-video"` in command prompt

### For linux 
1. Download `video-converter`
2. Run `video-converter --path "path-to-video"` in command prompt

### Example
**Linux:** <br>
`./video-converter --path (path)/video_converter/assets/BadApple.mp4 --fps 45.0 --autosize`

**Windows:** <br>
`video-converter.exe --path (path)/video_converter/assets/BadApple.mp4 --fps 45.0 --autosize`

### Arguments
- `--path` (required) - string path
- `--autosize` (false) - flag
- `--fps` (30) - float, must contain decimal, ex 30.0, 45.5
- `--size_x` (120) - int value
- `--size_y` (40) - int value
