QR code generator using python

Detailed Explanation:

Packages:
     1. qrcode - used to generate QR codes.
     2. validators - used to validate the input string whether it is valid or not.

Methods:
     1. is_valid_url - returns true if string is valid, otherwise false.
     2. generate_qr_code - 
                          i) Check for valid URL, If Invalid, It stops execution with return.
                         ii) Initializes qrcode object with settings (version[Controls size of QR (Depends on the input data)], 
                             error_correction[%of data can be restored], box_size[size of each box in grid], border[width of box]).
                        iii) Adds data to QR code.
                         iv) Adjusts QR size to fit the data.
                          v) Generates QR code with input colors and filename.