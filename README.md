TAMUHACK X Project Submission 

I'll save you the read before you get too far, SafeSurf doesnt work. 

This project was designed for the 2024 TAMUhack X hackathon, and was intended to create a chrome enabled browser extention for children that would block "adult" websites, then would prompt for camera access and use OpenCV in python to determine the users age, then to conditionally return access. For a number of factors, two team members dropped and the project didnt get as far as it should have. Out of integrity of what was accomplished in the time provided, I think it is incredibly important to keep the files up and availible, even if a display of suboptimal work.

Initially the project was broken into 4 categories: front end, back end, python opencv age detection (me), and hardware/electronics for the demo. The team members for front end and back end both had to leave for personal reasons, so I ended up picking up both. 
 - Frontend: the html ended up being fairly basic, but was tricky in getting the call out through the js to the python server, and in that chain, I am still not certain where the disconnect came from. The html is very primative, but they work and thats enough.
 - Backend: for the extention the manifest file ended up being substantially more of a headache than it should have been because the convenient website blocker is for manifest versions 2 and under, whereas the ability to call a function from a python server came from the manifest versions 3, and so I spent some time fighting to block websites in manifest 3 (unsuccessfully). Frankly, I think the backend is where most of the issues arose from, and likely where they still are, but to our credit, none of us had written in js before starting the project.
 - The python server was my baby. I initially got the face recognition working, then changed the structure into callable methods, hosted a local server, then started the server on the local machine. I am fairly confident that the python server is working.
 - The hardware went beautifully, and I have no notes for sean. He put everything together quickly and efficiently, and knew what he was doing, but neither of us knew how to do web dev so we both just floudered for a long time on that.

Overall, I think that the project and the hackathon as a whole was beneficial in how we learned something new and grew, and personally, I look forward to applying my skills learned onto a project with TURTLE at A&M. Knowing what I know now, I would not hesitate to do it again, and although we didn't complete our project, I can't wait for the next hackathon.
