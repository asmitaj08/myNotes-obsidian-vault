---

kanban-plugin: board

---

## #backlogs



## #to-do

- [ ] Introduce the vulnerability in the custom binary and test if it can be detected
- [ ] Identify when to start and stop one fuzz run
- [ ] Discuss with Dominik and Marius
- [ ] identify how to deal with delay() in firmware
- [ ] Create generalized renode module for I2C peripheral
- [ ] Test with practical firmwares from previous research papers
- [ ] Work on how to process input if different bytes are resposible for updating different parameters, maybe do slicing (as currently I am just taking the byte at 0th index of the fuzz value provided by LibAFL)
- [ ] Improve on LibAFL side the input generation and mutation part
- [ ] Improve on libafl side regarding feedback and executor


## #in-progress

- [ ] Test the new custom binary for BMP180 with nrf52840
- [ ] Identify the issue, and fix BMP180.cs sensor file in Renode


## #completed

**Complete**




%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[false,false,false,false]}
```
%%