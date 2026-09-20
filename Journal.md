# Journal
Write your Journal questions and notes here.

Phase 1-
  assets:
    - assets/images/alice.jpg
    - assets/images/bobby.jpg
    - assets/images/carol.jpg
    - assets/images/cindy.jpg
    - assets/images/greg.jpg
    - assets/images/jan.jpg
    - assets/images/marcia.jpg
    - assets/images/mike.jpg
    - assets/images/peter.jpg
Is exactly how it is in the yaml 2x space to indent within flutter: the 2x more space for each asset declaration. If not container constrait is placed on an image it can take up more space than intented. especially with larger images then can coninue on off the screen. The BoxFit.cover scales the image to fit in a container while trying to maintain aspect ratio. 

Phase 2-
If you take away expanded from one of the tiles it takes up more space due to it not being evenly divided with the others anymore. The expanded works with the row to figure out an even spacing for the elements using expanded and uses this height and width when displayed the wraped widgets.

Phase 3-
Nesting the expanded widgets for the rows and rows child widgets follows the golden rule, because it puts even contraints on the height and width of each bradyTile to fit evenly on screen.

phase 4-
The grid view with the crossAsixCount setting seems to be alot easier in my opinion. To get this 3x3 grid the GridView.count() is the way to go, while not as flexible as the expanded nesting it is way easier to setup. for a true grid view this creates a even gride with fewer lines, but if you want a non-standard grid, this is where the nested expanded widgets will do better.
