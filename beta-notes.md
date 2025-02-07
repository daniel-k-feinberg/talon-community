# Mixed Mode
in your command_and_dictation_mode.talon, add at the bottom:

^mixed mode$:
  mode.disable("sleep")
  mode.enable("dictation")
  mode.enable("command")

(note this will not behave correctly on public Talon, it
 depends on a feature of the beta)

# Parrot Integration

Extract these files into your Talon Home (~/.talon) directory: parrot_example.zip

See also #ext-parrot

# Webspeech Engine

This is mostly useful for dictation (not commands) in languages other than English.

1. Add this repository to your Talon user/ directory: webspeech_examples
2. While Talon is running, open http://localhost:7419 in Chrome. You'll probably also need to allow microphone access to Chrome the first time you enable it.
3. See the commands here to switch languages: https://github.com/talonvoice/webspeech_examples/blob/main/languages.talon

