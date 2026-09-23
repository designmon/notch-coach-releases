# Notch Coach

A meeting coach that lives in your MacBook's notch. It listens, shows you the words to say next,
and writes the recap afterwards.

**[Download the latest version](https://github.com/designmon/notch-coach-releases/releases/latest)** · macOS 14.2+ on Apple Silicon

Unzip it, drag **Notch Coach** to Applications, then **right-click it → Open → Open** the first
time. (It is signed but not notarized by Apple, so macOS asks once.) After that it updates itself.

On first run it asks for the microphone, the call's audio, and your calendar, and for an
[OpenRouter](https://openrouter.ai) key, which is what writes the lines.

Your audio never leaves your Mac: speech recognition runs on-device. Only short pieces of text are
sent, to write the lines and the recap.
