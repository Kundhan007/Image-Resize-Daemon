

## **Objective**:
This background application continuously(event based) monitors the clipboard and resizes any image in the clipboard
to a predefined size (width) if it exists.

## **Features**:
Background Operation: The application runs in the background and waits for a clipboard event.
Event-Based: The application activates only when cmd+c (copy) is pressed, checking if the clipboard contains an image.
Image Resizing: If the clipboard contains an image, it is resized to the specified width, while maintaining the aspect ratio.
Graceful Termination: The application can be killed with the cmd+q hotkey.



## **Usage**:

#### 1. **Run the Application**:
Start the clipboard monitor by running the following command:
```bash
python clipboard_resizer/main.py
```

#### **2. Trigger the App:**
Copy an image (e.g., by pressing cmd+c on an image file or image content).
The application will automatically detect the image in the clipboard and resize it to the predefined width.


## **logging information**:
logging information can be seen in logs/log.txt