- Add documentation
- Figure out how devShells are supposed to work.
- Get jaylib to work on a binscript
- Ensure names are consistent with how other languages are packaged in nix.
    - mkJanetPackage vs buildJanetPackage?
    - withJanetPackages vs dependencies?
- should mkJanetScript create a binscript instead of executible?
    - benefit: client code doesn't have to include a main function.
    - drawback: harder to distribute? maybe?
    - If I do this, I should update the tests to ensure I still have good
      coverage of both declare-executable and declare-binscript.V
