### Sword Kirby body
To create our Sword Kirby we will need to create hands, feet, a hat, and a sword. We will start with simplest components and finish with the most complex. First, using the rotate tool we are going to tilt our prefab Kirby's body on the z-axis so his body is leaning slightly to the right. 

This will be our base:

<img width="400" alt="Screenshot 2024-09-12 at 9 48 16 PM" src="https://github.com/user-attachments/assets/ae3a1bc7-3dcf-4222-ba20-11e4c88a8096">


### Kirby's hands
The hands are composed of two capsules. Create a capsule object and scale to a larger size. Width-wise they should be larger than the eyes. The left hand will hold the sword therefore this hand will be place on the lower left side of the body. Attach the the capsule to the body until ony a round looking shape is sticking out, this will be the hand. 

<img width="400" alt="Screenshot 2024-09-12 at 9 58 37 PM" src="https://github.com/user-attachments/assets/7d2a75cd-239a-4abf-aa41-25b772531123">

These are the values for refrence:

<img width="400" alt="Screenshot 2024-09-12 at 9 51 52 PM" src="https://github.com/user-attachments/assets/e8541938-f94e-419f-a065-128f84d5fabc">

-Right hand
For the right hand duplicate the first capsule. This hand will be holding on to the hat so it doesn't fly away mid battle. Move and rotate the second capsule pointing upward on the right side of the body. At this stage it should look like Kirby is waving hello.

<img width="400" alt="Screenshot 2024-09-12 at 9 58 05 PM" src="https://github.com/user-attachments/assets/c6213c02-1048-4940-bd85-2333e444240e">


### Kirby's feet
For this variant Kirby will look like he is running. To create the feet we will also use two capsules. For the left foot (this will be the one that is behind the body pushing kirby forward), first place and adjust a capsule object to a larger size flattening slightly. Rotate until the pointing downward to the left and attach behind the left arm we first created.

<img width="400" alt="Screenshot 2024-09-12 at 10 14 41 PM" src="https://github.com/user-attachments/assets/68c8b64d-c670-4c08-8a41-a0c2a5349df5">


The right foot will be a duplicate of our first object to save time. This will be the front foot. Adjust the scale size to be larger than the first to create a more effective look. Move and rotate the cpasule until it is flat and faceing slightly to the right.

<img width="400" alt="Screenshot 2024-09-12 at 10 08 46 PM" src="https://github.com/user-attachments/assets/2c775e5a-7016-4238-a80e-151800dceb79">


### Kirby's hat
Create a sphere object, scale to be almost as big as the body. Attach to the top of Kirby's head leaving more than half the sphere out. 

<img width="400" alt="Screenshot 2024-09-12 at 10 19 54 PM" src="https://github.com/user-attachments/assets/a6cf530e-e438-43ef-b5d5-ee14e0e7f798">

Create a cylinder object and place inside the sphere layer to create a folder for the hat. The cylinder will be the border of the hat. Flatten and the cylinder and scale. The height should roughly be the same as the eyes and the width should be slightly bigger than the body's width. Place cylinder between the line that connects the base of the hat and the body.

<img width="400" alt="Screenshot 2024-09-12 at 10 20 02 PM" src="https://github.com/user-attachments/assets/06903c60-837b-4270-b31e-982c2400fe05">

Now we want to build the shape of the hat. Create a capsule and scale to the shape of a small drum. This shape wil go on top our hat base. Attach so that only less than half of the capsule is sticking out. Rotate to the left so the right edge of of the capsule is looking up and is the only part left sticking out of the hat base. The rest should be concealed.

<img width="400" alt="Screenshot 2024-09-12 at 10 20 13 PM" src="https://github.com/user-attachments/assets/d11420a8-61f1-4af7-be06-1f4916a96419">

Alternative view:
<img width="400" alt="Screenshot 2024-09-12 at 10 23 04 PM" src="https://github.com/user-attachments/assets/b9d968c0-858a-46e9-b13a-f6a2364f9b8c">

This stepe is a little tricky. These are the exact values used:
<img width="395" alt="Screenshot 2024-09-12 at 10 23 15 PM" src="https://github.com/user-attachments/assets/3fd9dbaa-822a-4082-a96f-1ff7eb61d428">

Next place another capsule object on top. This one will be more pill-shaped but slightly flatter. Rotate until it's mostly on it's side with the left side only slightly tilted up. Attach this to the former capsule that was created.
<img width="400" alt="Screenshot 2024-09-12 at 10 20 31 PM" src="https://github.com/user-attachments/assets/667b87bd-6459-46ed-a308-c1409b061cfd">


Finally create a sphere and place on the last capsule's end.
<img width="400" alt="Screenshot 2024-09-12 at 10 20 39 PM" src="https://github.com/user-attachments/assets/b4e8ef94-c831-4cd7-8eef-690b3e1c17e7">

### Kirby's sword


