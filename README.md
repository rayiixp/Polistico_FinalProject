<h1 align="center">Chicken Classifier Flutter App</h1>

<p align="center">
  A modern, user-friendly mobile application built with Flutter to identify 10 different chicken breeds using on-device machine learning.
</p>

---

## 🐔 About The Project

The Chicken Classifier app provides a simple yet powerful solution for poultry enthusiasts, backyard farmers, and curious individuals to identify chicken breeds instantly. By leveraging a custom-trained TensorFlow Lite model, the app analyzes images of chickens and provides a prediction with a confidence score, all directly on the user's device.

---

## ✨ Features

- **Instant Breed Identification:** Classify chickens by taking a photo or selecting one from the gallery.  
- **On-Device Machine Learning:** Uses a TFLite model for fast, offline-first predictions.  
- **Scan History:** Automatically saves every identification result to a persistent log using Firebase Cloud Firestore.  
- **Analytics Dashboard:** Visualizes your scan history with graphs showing breed frequency, distribution, and prediction confidence levels.  
- **Modern & Intuitive UI:** A clean, animated, and user-friendly interface designed for a seamless experience.  
- **Cloud Backup:** Images are backed up to Firebase Storage, ensuring your scan history is safe.

---


## 💻 Technology Stack

- **Framework:** Flutter  
- **Backend & Database:** Firebase (Cloud Firestore, Firebase Storage)  
- **Machine Learning:** TensorFlow Lite  
- **State Management:** setState / StreamBuilder for reactive UI updates from Firebase.  
- **UI/UX:** Custom-built widgets, animations, and a centralized theme.

---

## 🐓 Breeds Identified

The current version of the model is trained to identify the following 10 distinct chicken breeds:

### 1. Australorp
**Description:** The Australorp is a large, soft-feathered bird from Australia, known for its glossy black plumage that shines with a green and purple sheen. They are excellent egg-layers and hold world records for egg production. They have a calm and docile temperament, making them a popular choice for families and backyard flocks.

### 2. Dong Tao
**Description:** Also known as the "Dragon Chicken," the Dong Tao is a rare and unique Vietnamese breed famous for its incredibly large, thick, and scaly legs. Historically, they were bred for royalty and mandarins. Their meat is considered a delicacy, and their imposing appearance makes them a true novelty.

### 3. Leghorn
**Description:** The Leghorn is a highly energetic and productive breed originating from Italy. They are most famous for being prolific layers of large white eggs. Typically white, they can also come in other colors. Leghorns are active foragers, intelligent, and can be quite noisy, making them better suited for free-range environments than confinement.

### 4. Orpington
**Description:** Originating from the United Kingdom, the Orpington is a large, fluffy bird bred to be an excellent egg-layer and a good table bird. The "Buff Orpington" is the most popular variety, known for its beautiful golden-buff feathers. They are extremely friendly, calm, and make great mothers, often referred to as the "golden retrievers" of the chicken world.

### 5. Plymouth Rock
**Description:** The Plymouth Rock is a classic American breed, valued for its dual-purpose qualities of providing both eggs and meat. The most common variety is the "Barred Rock," which has a distinctive pattern of black and white stripes. They are known for being hardy, friendly, and reliable layers of large brown eggs.

### 6. Rhode Island Red
**Description:** One of the most famous American breeds, the Rhode Island Red is a dual-purpose chicken renowned for its hardiness and outstanding egg-laying abilities, producing a high volume of brown eggs. They have a deep mahogany-red color and are known for their tough and utilitarian nature, making them one of the most successful and popular backyard breeds.

### 7. Shamo
**Description:** The Shamo is a Japanese breed of gamefowl known for its tall, upright stance, muscular build, and sparse feathering. They were originally bred for cockfighting and are known for their power, stamina, and aggressive temperament. With their fierce, almost reptilian appearance, they are primarily kept by collectors and breeders for exhibition today.

### 8. Silkie
**Description:** Silkies are one of the most unique and beloved ornamental breeds. They are famous for their fluffy, silk-like feathers that feel like fur. Uniquely, they have black skin and bones, blue earlobes, and five toes on each foot instead of the usual four. They have a very sweet and gentle temperament and are known for being excellent mothers.

### 9. Sussex
**Description:** The Sussex is a historic English breed that is prized as a dual-purpose bird for both eggs and meat. The "Speckled Sussex" is particularly popular, with mahogany feathers that are tipped with white, a pattern that becomes more beautiful with each molt. They are curious, calm, and excellent foragers, making them a great addition to any flock.

### 10. Wyandotte
**Description:** The Wyandotte is an American breed known for its round, curvy body and good-natured disposition. They are a dual-purpose breed and are very winter-hardy thanks to their dense feathering and rose comb. The Silver Laced Wyandotte, with its striking black-edged white feathers, is one of the most beautiful and iconic chicken varieties.
