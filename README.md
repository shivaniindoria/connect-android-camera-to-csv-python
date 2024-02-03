
# Android Camera Stream with Python

This Python script captures and displays a live stream from an Android camera using OpenCV and requests library.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- imutils (`pip install imutils`)
- Requests (`pip install requests`)

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/shivaniindoria/android-camera-stream.git
   cd android-camera-stream
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and install **IP Webcam** application on your mobile phone.  
     - Then make sure your PC and Phone both are connected to the same network.  
     - Open your IP Webcam application on your both, click “**Start Server**” (usually found under top three lines).  
     - This will open a camera on your Phone.  
     - A URL is being displayed on the Phone screen, use the same `url` in your Code.  

4. Replace the `url` variable in the script with the correct URL for your Android camera.

5. Run the script:
   ```bash
   python android_camera_stream.py
   ```

Press the 'Esc' key to exit the stream.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [OpenCV](https://opencv.org/) for the powerful computer vision library.
- Special thanks to the contributors of [imutils](https://github.com/jrosebr1/imutils) for simplifying image processing tasks.
