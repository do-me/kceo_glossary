# KCEO Glossary

Test repo for KCEO glossary

### Mac build error
If error `ERROR   -  "cairosvg" Python module is installed, but it crashed with:` just use:

`export DYLD_FALLBACK_LIBRARY_PATH=/opt/homebrew/lib` before. Or set it once, e.g. for zsh shell: 

`echo 'export DYLD_FALLBACK_LIBRARY_PATH=/opt/homebrew/lib' >> ~/.zshrc && source ~/.zshrc`

### Installation commands 
See ci.yml.
