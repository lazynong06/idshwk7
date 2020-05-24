### How I hid my information
1. Add raw.png and info file. raw.png is the information carrier and info store the information temporarily.
2. Use pipe command 'cat raw.png info > test.png'to concatenate two original files, and write the result to test.png.
3. The information is not visible when test.png is opened in a normal way.

### How I extracted information
1. Use command 'strings test.png' then the information I hid appears in the end of the file.
