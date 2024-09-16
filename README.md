# What-is-a-QR-code
QR codes are used to encode and decode the data into a machine-readable form. The use of camera phones to read two-dimensional barcodes for various purposes is currently a popular topic in both types of research and practical applications. 
import pyqrcode 
from pyqrcode import QRCode 
  
# String which represent the QR code 
s = "https://www.youtube.com/channel/UCeO9hPCfRzqb2yTuAn713Mg"
  
# Generate QR code 
url = pyqrcode.create(s) 
  
# Create and save the png file naming "myqr.png" 
url.svg("myyoutube.svg", scale = 8) 
