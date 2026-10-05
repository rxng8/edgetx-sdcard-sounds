# Build Notes

```bash
conda create -n edgetx python=3.10
conda activiate edgetx
```

```bash
sudo apt install libportaudio2 portaudio19-dev libasound-dev -y
pip install elevenlabs
```

```bash
# export ELEVENLABS_API_KEY="<API_KEY>"
export ELEVENLABS_API_KEY="sk_a1153d71bc3326acc9c77b1ccedb572ce546fdf4643c1b8c"
```


```bash
export ELEVENLABS_API_KEY="sk_a1153d71bc3326acc9c77b1ccedb572ce546fdf4643c1b8c" && python3 voice-gen-elevenlabs.py
```