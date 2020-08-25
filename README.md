# Grindstone

So, before the pandemic hit I was working on brushing up my game development skills by creating a project in UE4. Mostly this was for my own entertainment, to see how the engine works and mostly was interested in the particle system. But I really enjoyed developing in the blueprint engine.

# Caution graphic violence warning

By modern standards it's quite cartoonish but it's worth noting there are simulated guns and blood in the videos below.

# tldr; check out video 10

The goal with this originally to make a cartoonish puzzle based physics single player shooter with only 3 to 5 levels or something. I wanted it to be a demo to show off to potential employers that I can do game development.

Was hoping to go to GDC this year, show off the Arduboy to get them to go view my portfolio which would have this in it.

I've posted all these videos unlisted on my own youtube because it wasn't originally intended to be shared, I was just sending it to my friends as I was working on it.

But seeing the project may not really go anywhere, I thought I would post the development videos here so people could see them.

It's based off this pack: 
https://www.unrealengine.com/marketplace/en-US/product/advanced-locomotion-system-v1

And I used that as a base and added some simple game code. Actually trying to figure out how to use the animation system was beyond me, and still remains the last hurdle in actually doing what I want with the engine. Everything else I'm pretty happy with just need to be able to add new animations and poses.

# Click the link for videos

Feedback is welcome!

[![Alt text](https://img.youtube.com/vi/nZsjWYCDuBo/0.jpg)](https://www.youtube.com/watch?v=nZsjWYCDuBo)

Getting the gun working, none of the props did anything in the original demo. Bullets are fired fired straight out of the muzzle and it doesn't pay attention if you are aiming or not so you can shoot randomly and it looks pretty wild.

[![Alt text](https://img.youtube.com/vi/59UGgQ9TGJY/0.jpg)](https://www.youtube.com/watch?v=59UGgQ9TGJY)

Added confetti coming out of the box just for fun trying out 3d particles.

[![Alt text](https://img.youtube.com/vi/RiVbbdhl0ow/0.jpg)](https://www.youtube.com/watch?v=RiVbbdhl0ow)

Added all the weapons into the playing field and enabled picking up, dropping and using of different objects. The pistol shoots, the torch has a magical effect that gets bigger when you click, the bow and arrow works as expected, the barrel spills oil, and the binoculars zoom in (recognize the shape?).

[![Alt text](https://img.youtube.com/vi/Lra-POXaxhs/0.jpg)](https://www.youtube.com/watch?v=Lra-POXaxhs)

Bullets now add physics impulses to other objects. You can knock objects out of NPCs hands.

[![Alt text](https://img.youtube.com/vi/odvk8Ytxumk/0.jpg)](https://www.youtube.com/watch?v=odvk8Ytxumk)

Bullets now draw tracer effects. Arrows now stick into walls and can be knocked down by walking into them. Knocking objects out of NPCs hands sets the pose to neutral. Bullets now draw blood and cause damage. NPCs with no health remaining switch to ragdoll. I reconsider my actions in the end.

[![Alt text](https://img.youtube.com/vi/vtc2VV1d6Lg/0.jpg)](https://www.youtube.com/watch?v=vtc2VV1d6Lg)

Bullets now trace to camera center point. Target barrels and boxes added to the level. Rocket Launcher and Pulse Cannon added to the game and level. Rocket projectiles create smoke and cause damage but do not create any physics impulses. 

# Video 10, check this one out!
Headphone warning!

[![Alt text](https://img.youtube.com/vi/ia5PK35nQM4/0.jpg)](https://www.youtube.com/watch?v=ia5PK35nQM4)

Added object highlights and bullet holes. Oil spill from the barrel now leaves oil on the ground. Bullet holes and oil spills decals have a maximum spawn managed globally and slowly decrease in size over time. Blood decals are added. Head shots do extra damage and spawn extra blood particles. Rockets now explode causing radial physics damage. NPCs that fall over and still alive get back up dynamically.

[![Alt text](https://img.youtube.com/vi/R57j69paGSg/0.jpg)](https://www.youtube.com/watch?v=R57j69paGSg)

Added bloody footprints.

[![Alt text](https://img.youtube.com/vi/Z7NGZVl6OzU/0.jpg)](https://www.youtube.com/watch?v=Z7NGZVl6OzU)

Stepping in oil and blood now causes footprints. Head shots now explode the head and have more blood particles.

[![Alt text](https://img.youtube.com/vi/rODXDiNneOI/0.jpg)](https://www.youtube.com/watch?v=rODXDiNneOI)

Added modular character models with ponytail physics! Starts to look like a game now!

[![Alt text](https://img.youtube.com/vi/mWobgiMCyYU/0.jpg)](https://www.youtube.com/watch?v=mWobgiMCyYU)

Added free runner test level with. Mostly as a joke.

[![Alt text](https://img.youtube.com/vi/V9WJSgB_wZY/0.jpg)](https://www.youtube.com/watch?v=V9WJSgB_wZY)

Camera pushes in from walls to avoid being obscured. Refined aiming for situations where the camera is obscured. Demonstrated with debug traces drawn.

[![Alt text](https://img.youtube.com/vi/Z4QQENU8Zts/0.jpg)](https://www.youtube.com/watch?v=Z4QQENU8Zts)

Arrow aiming now focused on camera center point and accounts for aiming above a target to get the correct arc. Arrows now damage and stick in NPCs. NPCs damaged below a threshold drop their object and take an injured pose.

[![Alt text](https://img.youtube.com/vi/D8Hg3f-Ddwc/0.jpg)](https://www.youtube.com/watch?v=D8Hg3f-Ddwc)

Textures added to blood particle and splatter effects. Footprint texture added. Decals fade out over time dynamically according to a height map.

[![Alt text](https://img.youtube.com/vi/KoBR8wCi6kk/0.jpg)](https://www.youtube.com/watch?v=KoBR8wCi6kk)

Untextured first couple rooms of Doom's E1M1 is created as a level.

[![Alt text](https://img.youtube.com/vi/zUR2Kj_mYzc/0.jpg)](https://www.youtube.com/watch?v=zUR2Kj_mYzc)

Procedural textures added. Aiming to camera center point refined and demonstrated with debug tracers drawn.

[![Alt text](https://img.youtube.com/vi/QEB5ntpuBDc/0.jpg)](https://www.youtube.com/watch?v=QEB5ntpuBDc)

Complete E1M1 test level created including landscape and water planes. Acid and water texture procedrually animated and interactive dynamic bump map that ripples when shot or walked through.

[![Alt text](https://img.youtube.com/vi/AWUi4u2ZWZs/0.jpg)](https://www.youtube.com/watch?v=AWUi4u2ZWZs)

Added a water acid pool to the test level. Added acid particles when interacting with the surface. Camera effect when submerged. Basic object boyancy added. Acid footsteps added.

[![Alt text](https://img.youtube.com/vi/jYJxF881_xc/0.jpg)](https://www.youtube.com/watch?v=jYJxF881_xc)

Testing a more advanced boyancy model.

Aaaaand that's it folks. That's about when I gave up because at this point I wanted to add animation of actually picking up objects and I couldnt figure it out and also the pandemic was giving me panic attacks whenver I tried to sit down and code.
