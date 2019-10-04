# Issues with the Mandi India tutorial

 * The top-level of the tutorial contains a second, singular top-level "AiiDA hands-on materials" section.
   That makes it more difficult to navigate the tutorial.
 * I did not test the windows section.
 * The Windows section appears to use different filenames for the private ssh key.
 * It would probably a good idea to have users create a working directory such as `~/tutorial/` instead of having them work in their home directories.
 * It seems unintuitive and annoying that in order to configure a second computer, we require two different configuration files and configuration commands.
   Especially since we were promised a few lines earlier that switching to a separate computer "means changing one line of code".
 * **I am unable to test proper connection to neighbor machines as the SSH configuration is not properly set up.**
 * It might be better to start the jupyter notebook *later*, since we do not actually interact with it for a while.
 * I'm asked to compare the submission script to the previous one, but I don't remember inspecting it previously.
 * **It appears that the PwCalculation (PK=184) failed; it remains in state "Waiting".**
