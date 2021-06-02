## Initially you have to goto the research folder and open command prompt and run the following code.

```bash
for /f %i in ('dir /b object_detection\protos\*.proto') do protoc object_detection\protos\%i --python_out=.
```
## Next run all the code cells in object-detection.ipynb 
