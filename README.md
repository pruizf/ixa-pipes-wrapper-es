# ixa-pipes-wrapper-es
Bash wrapper for IXA Pipes Spanish web-services

Will start web-services if needed and run (with Spanish models):

- tokenization 
- pos-tagging (choose from two models)
- constituency parsing
- dependency parsing
- optionally: semantic role labeling (SRL)

## Usage

```
  ./run_nlp.sh input_dir output_dir postagger_type(def|alt) [only_deps]
  
  Note:
  - postagger_type can only be 'def' or 'alt'
  - Leave 'only_deps' blank if want to get SRL results besides dependency parsing
```

Stop the services with `./stop_nlp.sh`

_sh_ files must be executable (chmod +x file_name)


[[Back]](http://github.com/pruizf/corpuswk)
