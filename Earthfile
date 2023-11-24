VERSION --use-function-keyword 0.7

COPY_CAT:
  FUNCTION
  COPY message.txt ./
  RUN cat message.txt

TOUCH:
  FUNCTION
  ARG file=touched
  RUN touch $file
