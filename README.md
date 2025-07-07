# Image-Resizer-

### 📋 Short Description

> A Python script to resize an image by a specified percentage using OpenCV and save the resized image.


### 📄 Folder Structure

/image-resizer/
├── image_resizer.py
├── imagepy.jpg      # (your input image)
├── newImage.jpg      # (output image after running script)
├── README.md



# 🖼️ Image Resizer

This Python script resizes an image to a specified percentage of its original size and saves the output using OpenCV.

---

## 🚀 Features
✅ Resize any image by specifying a scale percentage  
✅ Saves the resized image to disk  
✅ Lightweight and easy to use  
✅ Works with most image formats supported by OpenCV

---

## 📋 How to Run

### 1️⃣ Install dependencies
Make sure you have Python 3 installed, then install OpenCV:
```bash
pip install opencv-python
````

### 2️⃣ Place your input image

Save your input image in the project folder and update the `source` variable in the script:

```python
source = "your_image.jpg"
```

### 3️⃣ Configure the scale

Set the desired resize percentage:

```python
scale_percent = 50
```

### 4️⃣ Run the script

```bash
python image_resizer.py
```

* The resized image will be saved as `newImage.jpg` in the same folder.

---

## 📄 Example

| Parameter    | Value          |
| ------------ | -------------- |
| Input Image  | `imagepy.jpg`  |
| Scale        | `50%`          |
| Output Image | `newImage.jpg` |


## 🧰 Technologies Used

* Python 3.x
* OpenCV (`cv2`)

## 📚 Notes

⚡ Works offline, no internet required.
⚡ Supports formats like JPG, PNG, BMP, etc.
⚡ You can adjust the `scale_percent` to enlarge or shrink images.


