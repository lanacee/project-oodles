# Oodles of Oodles
The dog breed name generator for poodle mixes

## About oodles

Poodle crosses/hybrids/mixes (aka oodles or doodles) are some of the most popular dog breeds in Australia.

While many of us can now identify a cavoodle, labradoodle or groodle at the dog park, there seems to be an ever-increasing list of new and unique poodle cross breeds.

I wanted to create an app that could generate an oodle breed name for any breed.

## Wireframe

[Wireframe](/Wireframe.png)

## How the app works

I used the [TheDogApi](https://docs.thedogapi.com/) for the list of dog breeds, photos and dog breed information.

The Oodles of Oodles app first checks against a list of known poodle breed mix names (this list is not exhaustive) and if it finds a match it will use this result.

| Breed A                       | Breed B | Name                   |
|-------------------------------|---------|------------------------|
| Labrador                      | Poodle  | Labradoodle            |
| Cavalier King Charles Spaniel | Poodle  | Cavoodle, Cavapoo      |
| Cocker Spaniel                | Poodle  | Spoodle, Cockapoo      |
| Maltese                       | Poodle  | Moodle, Maltipoo       |
| Schnauzer                     | Poodle  | Schnoodle              |
| Golden retriever              | Poodle  | Groodle, Goldendoodle  |
| Old English Sheep Dog         | Poodle  | Sheepadoodle           |
| Yorkshire Terrier             | Poodle  | Yorkiepoo              |
| Shih Tzu                      | Poodle  | Shoodle, Shihpoo       |
| Chihuahua                     | Poodle  | Chipoo, Poochi         |
| Tibetan Spaniel               | Poodle  | Tiboodle               |
| Bernese Mountain Dog          | Poodle  | Bernedoodle            |
| Border Collie                 | Poodle  | Bordoodle              |
| Australian Shephard           | Poodle  | Aussiedoodle           |
| English Springer Spaniel      | Poodle  | Springerdoodle, Sproodle, Springerpoo |
| Soft-Coated Wheaten Terrier   | Poodle  | Whoodle                |
| West Highland White Terrier   | Poodle  | Westiepoo              | 
| Weimaraner                    | Poodle  | Weimardoodle           |
| Pomeranian                    | Poodle  | Pomapoo                |
| Havanese                      | Poodle  | Havapoo, Havadoodle, Poovanese |
| Bichon Frise                    | Poodle  | Poochon, Bichpoo, Bichoodle                |
| Pekingese               | Poodle  | Peekapoo               |

If it does not find a match the app will generate suggestions for a new oodle breed name. These are based on patterns from existing oodle breed names:

- first letter of breed A + oodle (e.g. Moodle)
- first two letters of breed A + oodle (e.g. Spoodle, Schoodle)
- first three letters of breed A + oodle (e.g. Cavoodle, Tiboodle, Bordoodle)
- first four letters of breed A + oodle (e.g. Schnoodle)


- first five letters of breed A + doodle (e.g. Bernedoodle)
- first six letters of breed A + doodle (e.g. Aussiedoodle, Goldendoodle, Weimardoodle)

- first four letters of breed A + poo (e.g. Cavapoo)
- first five letters of breed A + poo (e.g. Cockapoo, Maltipoo)
- first six letters of breed A + poo (e.g. Westiepoo)
