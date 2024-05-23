<h4>Error ที่พบบ่อย</h4>
<h5>Traceback (most recent call last):
  File "d:/Python Gui Practice/RenameFile/app.py", line 9, in <module>
    output.save(output_path)
  File "C:\ProgramData\Anaconda3\lib\site-packages\PIL\Image.py", line 2235, in save
    save_handler(self, fp, filename)
  File "C:\ProgramData\Anaconda3\lib\site-packages\PIL\JpegImagePlugin.py", line 631, in _save
    raise OSError(f"cannot write mode {im.mode} as JPEG") from e
OSError: cannot write mode RGBA as JPEG</h5>
    ![image](https://github.com/dooddyfire/Remove-Background-From-Image-Using-Python/assets/49072725/c8ecb438-4b81-4841-bf46-c57bdb6c982b)

<h5>ให้เช็คนามสกุลไฟล์ output เราต้องใส่เป็น .png (ดูที่ตัวแปร output_path)</h5>
