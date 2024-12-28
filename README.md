<h1>QR code generator using python</h1>

<h2>Detailed Explanation:</h2>


<p><h3>Packages:</h3><br>
      &emsp;1. qrcode - used to generate QR codes.<br>
      &emsp;2. validators - used to validate the input string whether it is valid or not.<br><br>

<h3>Methods:</h3><br>
      &emsp;1. is_valid_url - returns true if string is valid, otherwise false.<br>
      &emsp;2. generate_qr_code - <br>
                        &emsp; &emsp;i) Check for valid URL, If Invalid, It stops execution with return.<br>
                          &emsp; &emsp;ii) Initializes qrcode object with settings (version[Controls size of QR (Depends on the input data)], error_correction<br>
                           &emsp; &emsp; &emsp;[% of data can be restored], box_size[size of each box in grid], border[width of box]).<br>
                         &emsp; &emsp;iii) Adds data to QR code.<br>
                         &emsp;  &emsp;iv) Adjusts QR size to fit the data.<br>
                         &emsp;   &emsp;v) Generates QR code with input colors and filename.<br>
</p>
