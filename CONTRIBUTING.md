# Contributing to the RI Reasoning Model

The RI Reasoning Model is a project focused on building AI that enhances human thinking through collaboration. Contributions from anyone interested in advancing this goal are encouraged.

## How to Add a Version

1. **Fork the Repository**  
   - Click "Fork" on the [GitHub page]( https://github.com/Turivny/RI-Reasoning-Model) to create a personal copy.
  
2. **Create a Branch**  
   - In the forked repository, start a new branch (e.g., `feature/vX.Y.Z-yourname`), where `X.Y.Z` is the version number you are contributing to, and `yourname` is your GitHub username or identifier.

3. **Add a Version File and Examples**  
   - Determine the minor version `vX.Y` you are contributing to. For example, if you are making changes based on `v1.5`, then `X=1`, `Y=5`.  
   - In the `/model` folder, check if there is a subfolder named `RI-Reasoning-Model-vX.Y`. If not, create it. This folder will contain all minor changes for that version (e.g., `RI-Reasoning-Model-v1.5`).  
   - Inside the subfolder `RI-Reasoning-Model-vX.Y`, create a file named `RI-Reasoning-Model-vX.Y.Z-yourname.md`, where `Z` is the patch version (start with `0` if it’s your first contribution to this minor version). For example: `RI-Reasoning-Model-v1.5.0-turivny.md`.  
   - In the same subfolder, create an examples file named `RI-Reasoning-Model-vX.Y.Z-yourname-examples-language.md`, where `language` is the language of the examples (e.g., `en` for English). For example: `RI-Reasoning-Model-v1.5.0-turivny-examples-en.md`.  
   - The version file (`RI-Reasoning-Model-vX.Y.Z-yourname.md`) should include:  
     - The code, with clear comments so it’s understandable without extra materials. Maintain readability with consistent formatting.  
     - An explanation of how it works or what’s improved. Clearly document parameter changes or architectural modifications.  
   - The examples file (`RI-Reasoning-Model-vX.Y.Z-yourname-examples-language.md`) should include examples demonstrating your enhancements.  
   - Check the [RI-Reasoning-Model-v1.5.0-turivny](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny.md) and [RI-Reasoning-Model-v1.5.0-turivny-examples-en.md](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny-examples-en.md) as references. Feel free to follow them as guides, but any new ideas or improvements are welcome!

4. **Update the README**  
   - In [README.md](README.md), under "Versions," add a new entry for your version, including links to both your model description file and your examples file. For example:  
      - **v1.5.0-turivny**
         - Initial release of the RI Reasoning Model, introducing the core framework for symbiotic human-AI collaboration.     
         - [RI-Reasoning-Model-v1.5.0-turivny](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny.md)
         - [RI-Reasoning-Model-v1.5.0-turivny-examples-en](./model/RI-Reasoning-Model-v1.5/RI-Reasoning-Model-v1.5.0-turivny-examples-en.md)

      
5. **Submit a Pull Request**  
   - Push the changes and open a pull request. Reviews will be completed within a week.

## Contribution Checklist
- [ ] Fork the repository
- [ ] Create a branch (e.g., `feature/vX.Y.Z-yourname`)
- [ ] Create or use subfolder `RI-Reasoning-Model-vX.Y` in `/model`
- [ ] Add version file `RI-Reasoning-Model-vX.Y.Z-yourname.md`
- [ ] Add examples file `RI-Reasoning-Model-vX.Y.Z-yourname-examples-language.md`
- [ ] Update `README.md` with links to version and examples files
- [ ] Submit a pull request

Contributions should consider all principles outlined in the [README.md](README.md). Thank you!
