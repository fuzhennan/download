# download
多线程断点续传下载
# 断点续传的条件：http响应头中 Accept-Ranges：bytes
# 如何写入文件：RandomAccessFile类
# 保持文件一致性： ETag || Last-Modified || crc32
