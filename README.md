# FM-Radio-Transmitter-LCD

### How to use
Step 1: Clone the repository on your raspberry pi
```
git clone https://github.com/ElectroBoy404NotFound/FM-Radio-Transmitter-LCD
```
Step 2: CD into the directory and run make (`sudo apt install make` if make does not exist)
```
cd FM-Radio-Transmitter-LCD
make
```
Step 3: Move the bin into /usr/bin
```
sudo mv fm_transimitter /usr/bin
```
Step 4: Play a song (.wav only)
```
sudo fm_transmitter -f 100 somg.wav
```
Step 5: Tune your fm radio to 100mhz and done!
