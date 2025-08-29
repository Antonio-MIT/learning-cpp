// REPO WILL LIKELY BE DELETED, THIS WAS JUST A TEST TO UNDERSTAND HOW THE PROCESS WORKS.


// learning-cpp
// "Just-in-case-I-need-this-later C++ experiments."
// Why is my fetch not pulling the .md file down to my localhost?
// Testing code in Visual Studio 2022.
// I am able to see a tree structure that was cloned to my localhost, but I don't know where to place the .cpp file for running C++ code?
// For example, if I compare two structures using the the CMD shell tool tree, I get two different results.
// The working example is fully loaded, but the failing example is not. 
// Both example, have some hidden directories .git and.vs
// Thinking, I should mirror the structure. I began doing this, however, and instead found that I was simply easier to use a pre-existing solution.
// To quickly bypass the gaps and missing files that came from clonig the default GitHub repo, I simply: Opened VS code > Created A New Project > Searched & Selected "C++ 
// Console App.

// [WORKING - t02-collaboration-team-aa]                       | [FAILING]
// C:.                                                         | C:.
// |   .gitattributes                                          | .gitattributes  # Create this.
// |   .gitignore                                              | .gitignore #Create this.
// |   main.cpp                                                | main.cpp 
// |   README.md                                               | README.md                                    
// |   rubber-ducks.sln                                        | PLACE-HOLDER.sln
// |   rubber-ducks.vcxproj                                    | PLACE-HOLDER.vcxproj
// |   rubber-ducks.vcxproj.filters                            | PLACE-HOLDER.vcxproj.filters
// |   rubber-ducks.vcxproj.user                               | PLACE-HOLDER.vcxproj.user
// |  
// +---rubber-ducks
// |   \---x64
// |       \---Debug
// |           |   main.obj
// |           |   rubber-ducks.exe.recipe
// |           |   rubber-ducks.ilk
// |           |   rubber-ducks.log
// |           |   vc143.idb
// |           |   vc143.pdb
// |           |
// |           \---rubber-ducks.tlog
// |                   CL.command.1.tlog
// |                   Cl.items.tlog
// |                   CL.read.1.tlog
// |                   CL.write.1.tlog
// |                   link.command.1.tlog
// |                   link.read.1.tlog
// |                   link.secondary.1.tlog
// |                   link.write.1.tlog
// |                   rubber-ducks.lastbuildstate
// |
// \---x64
    \---Debug
            rubber-ducks.exe
            rubber-ducks.pdb
