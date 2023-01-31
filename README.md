# ffmpeg_minimum

git clone --depth 1 https://github.com/FFmpeg/FFmpeg.git ffmpeg
      
      
      ./configure --enable-gpl --enable-nonfree \
      --enable-debug=3 --disable-optimizations \
      --arch=$arch --target-os=mingw32 \
      --cross-prefix=$host- --pkg-config=pkg-config --prefix=./
