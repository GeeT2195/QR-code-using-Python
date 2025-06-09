# QR-code-using-Python


# First install qrcode using the terminal by writing the command pip install qrcode and then import it
import qrcode

# Enter data in the qrcode
data = "Any type of data u want to show in qr code"

# For making qrcode
qr = qrcode.make(data)

# Saving the file in your computer 
qr.save("Geet2195_qr.png")

# Install pillow using the terminal by writing the command pip install pillow and then import it
from PIL import Image

# Make a variable and enter the path of saved file that you saved before 
img = Image.open("Geet2195_qr.png")

# Your output or QR code succesfully created
img.show()
