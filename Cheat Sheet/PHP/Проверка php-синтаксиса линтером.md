```bash
docker run --rm -it --name linter -v $(pwd)/www:/code pipelinecomponents/php-linter:amd64-0.13.1 parallel-lint --colors .
```
