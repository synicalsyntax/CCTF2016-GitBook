# Steggy (Forensics)
##About

Steggy was a challenge in the Forensics category worth 25 points. It was intended to be an easy challenge. The software was given to the competitors so that the main challenge would be focused on finding an operating system that could run wbStego4. 54 teams solved Steggy over the course of the competition.

##Description
Oh no! Something wrong happenned to the source text of the Stegosaurus article on Wikipedia!

Hint: wbStego4

###steggy.txt
```
Stegosaurus (/ˌstɛɡəˈsɔːrəs/[1]) is a type of armored dinosaur. Their fossil bones have been found in rocks dated to the Late Jurassic period (Kimmeridgian to early Tithonian ages), between 155 to 150 million years ago, in the western United States and Portugal. Several species have been classified in the upper Morrison Formation of the western U.S, though only three are universally recognized; S. stenops, S. ungulatus and S. sulcatus. The remains of over 80 individual animals of this genus have been found.[2] Stegosaurus would have lived alongside dinosaurs such as Apatosaurus, Diplodocus, Brachiosaurus, Allosaurus and Ceratosaurus; the latter two may have been predators of it.

These were a large, heavily built, herbivorous quadrupeds with rounded backs, short fore limbs, long hind limbs, and tails held high in the air. Due to their distinctive combination of broad, upright plates and tail tipped with spikes, Stegosaurus is one of the most recognizable kinds of dinosaur. The function of this array of plates and spikes has been the subject of much speculation among scientists. Today, it is generally agreed that their spikes were most likely used for defense against predators, while their plates may have been used primarily for display, and secondarily for thermoregulatory functions. Stegosaurus had a relatively low brain-to-body mass ratio. They had short necks and small heads, meaning they most likely ate low-lying bushes and shrubs. One species, Stegosaurus ungulatus, is the largest known of all the stegosaurians (bigger than related dinosaurs such as Kentrosaurus and Huayangosaurus).

Stegosaurus remains were first identified during the "Bone Wars" by Othniel Charles Marsh. The first known skeletons were fragmentary and the bones were scattered, and it would be many years before the true appearance of these animals, including their posture and plate arrangement, became well understood. The name Stegosaurus means "roof lizard" or "covered lizard", in reference to its bony plates.[3] Despite its popularity in books and film, mounted skeletons of Stegosaurus did not become a staple of major natural history museums until the mid-20th century, and many museums have had to assemble composite displays from several different specimens due to a lack of complete skeletons.

Source: https://en.wikipedia.org/wiki/Stegosaurus
```

##Solution
Look at the file. If it's the source text, why are there spaces between words missing? The file was probably messed with.

1. Download wbStego4.
2. Take the file steggy.txt and input it into the program.

In whatever text file you output the decoded message in, you should find the flag: **{t3Xt_with1n_text}**
