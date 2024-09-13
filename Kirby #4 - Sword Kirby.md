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
Create a sphere object, scale to be almost as big as the body. Attach to the top of Kirby's head leaving more than half of the sphere out. 

<img width="400" alt="Screenshot 2024-09-12 at 10 19 54 PM" src="https://github.com/user-attachments/assets/a6cf530e-e438-43ef-b5d5-ee14e0e7f798">

Create a cylinder object and place inside the sphere layer to create a folder for the hat. The cylinder will be the border of the hat. Flatten the cylinder and scale. The height should roughly be the same as the eyes and the width should be slightly bigger than the body's width. Place cylinder between the line that connects the base of the hat and the body.

<img width="400" alt="Screenshot 2024-09-12 at 10 20 02 PM" src="https://github.com/user-attachments/assets/06903c60-837b-4270-b31e-982c2400fe05">

Now we want to build the shape of the hat. Create a capsule object and scale to the shape of a small drum. This shape wil go on top of our hat base. Attach so that only less than half of the capsule is sticking out. Rotate to the left so the right edge of of the capsule is looking up and is the only part left sticking out of the hat base. The rest should be concealed.

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
Kirby's sword has a few details and lots of steps so follow along attentively.
Start by creating a cylinder object which will be the handle of the word. Scale to a small thin rod shape and attach to the middle of Kirby's left hand.

<img width="400" alt="Screenshot 2024-09-12 at 11 23 32 PM" src="https://github.com/user-attachments/assets/a2519c47-8af0-48b8-9c0d-c71dcee07764">

Create a shorter thicker cylinder to go on top of the handle. This will be where we place the decorative gem.

<img width="400" alt="Screenshot 2024-09-12 at 11 23 48 PM" src="https://github.com/user-attachments/assets/9b8bb39a-9fdd-404e-b7b5-41de50725df2">

For the decorative gem create a sphere and scale to an flat oval shape that is the height of the second cylinder we placed. Attach on the former cylinder. Duplicate the sphere object we created and scale to a slighlty smaller size. Attack on top of the bigger oval.

<img width="400" alt="Screenshot 2024-09-12 at 11 23 58 PM" src="https://github.com/user-attachments/assets/489a5e4b-0c71-4180-a0b6-fe3a2561d995">

Now the decorative side bars of the handle. Create a cylinder the scale to the same size as the handle and place vertically through the top cylinder that has the gem attached.

<img width="400" alt="Screenshot 2024-09-12 at 11 31 19 PM" src="https://github.com/user-attachments/assets/cd1894cb-c850-447b-a465-769572363586">

Add two small spheres on both ends.

<img width="400" alt="Screenshot 2024-09-12 at 11 31 59 PM" src="https://github.com/user-attachments/assets/9d9a43da-32cc-4176-a331-615b007648e0">

Now for the sword create a cube object and scale to a thin long rectangle. Place on the end of the sword and tilt the cube to the left. Duplicate and tilt the second cube to the right. There will be a gap in the middle (we'll fix it later).

<img width="400" alt="Screenshot 2024-09-12 at 11 32 32 PM" src="https://github.com/user-attachments/assets/fd80a22c-d6f8-49ea-a74e-18482c52464e">

Create two more cubes. Scale into rectangles that are the same thickness as the previous ones but much shorter. Place both rectangles on both ends of the sword and tilt inwards. Note that there will be a dimond shaped gap at the end.

<img width="400" alt="Screenshot 2024-09-12 at 11 36 07 PM" src="https://github.com/user-attachments/assets/e96de176-8bb4-407f-b6a8-0ea60f2e1454">

To make the tip of the sword duplicate one of the previously made smaller rectangles. Scale and rotate into a diamond shape. Place into the gap at the end of the sword.

<img width="400" alt="Screenshot 2024-09-12 at 11 36 21 PM" src="https://github.com/user-attachments/assets/fc7f21ac-1070-4431-999b-0d5cdfdb9f62">

To finish the sword duplicate one of the long rectangle pieces made and place in the middle to fill in the final gap of the sword.

<img width="400" alt="Screenshot 2024-09-12 at 11 36 21 PM" src="https://github.com/user-attachments/assets/6ad90b6d-4647-4051-bf6c-f0935e31ac10">

### Final details
One of the finishing touches for this Kirby are the angry eyebrows. To make this place a capsule object and scale into a tooth-pick shape. Rotate the shape down and place above and on top of the eye. Duplicate and repeat for other eye.

<img width="400" alt="Screenshot 2024-09-12 at 11 36 48 PM" src="https://github.com/user-attachments/assets/163d7dfc-2f96-4c84-a679-503bf526f2cd">

Done!

