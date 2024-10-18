* do not compare with existing pdf decoder, rather just train it specific to embedded systems
* Idea is to develop a interactive datasheet assistant (IDA) chatbot where user can query anything about specific MCUs. We will train this model with bunch of datasheet and possible questions where we can also leverage chatgpt and notebookLM to generate question and response for training
* Later pick up ideas as mentioned in Notes (Microsoft one note)
* Train model with the existing SVDs, and compare using SVD parser
* In paper, mention the importance of SVDs and why we need it

## Links for existing SVDs

1. CMSIS svd data : https://github.com/cmsis-svd/cmsis-svd-data/tree/main/data 
2. https://github.com/modm-io/cmsis-svd-stm32 (cmsis svd stm32)
3. https://github.com/espressif/svd/tree/main/svd (espressif esp32 svd)
4. https://github.com/AdaCore/svd2ada/tree/master/CMSIS-SVD (multiple vendors)
5. https://github.com/ARM-software/CMSIS_5/tree/develop/Device/ARM/SVD
6. Example svd - https://github.com/ARM-software/CMSIS_5/blob/develop/CMSIS/Utilities/ARM_Example.svd 
## SVD parsers 
1. cmsis-svd : https://github.com/cmsis-svd/cmsis-svd (**)
2. Rust svd-parser : https://github.com/rust-embedded/svd
3. https://pypi.org/project/svd2py/ (CMSIS SVD file parser that allows to convert SVD format to Python data structure, Parser does not check SVD file syntax. It assume that parsing file is a proper SVD file.)

## SVD use case 
1. https://arm-software.github.io/CMSIS_5/SVD/html/index.html (CMSIS SVD Benefits) 

## SVD generic info 
1. https://www.keil.com/pack/doc/CMSIS_Dev/SVD/html/svd_Format_pg.html
2. https://www.keil.com/pack/doc/CMSIS_Dev/SVD/html/schema_1_2_gr.html 
3. https://github.com/ARM-software/CMSIS_6 
4. https://arm-software.github.io/CMSIS_6/latest/General/index.html (can be used later with LLM to generate APIs for MCU)
