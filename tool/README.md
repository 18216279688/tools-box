# 工具使用说明
第一个工具用于把图片转换成TXT文件的Python小工具,用到了pillow等第三方库.原理是打开一幅图片,先对图片进行格式转换和缩放,然后对图像二值化,转换成纯黑白的图像,接着依次读取图片每个像素的值写入到文本文件中,如果该值不为0则写入@,否则写入空格.
第二个工具用来生成二维码，用到了qrcode等第三方库，输入要生成二维码的图片文件等，然后输出生成的二维码到桌面上.