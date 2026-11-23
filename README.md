# MC Candy Shell - Rap Battle Mod

A Minecraft (26.3, Fabric) mod where you rap battle an original boss, **MC Candy Shell**, a glossy green candy rapper.

Pick one of 4 rhyming lines each round, Pokemon style. Good rhymes drain his health bar, but the battle is rigged: you always lose in the end and get hit by a rainbow music-note beam.

## Status

- [x] Part 1: battle logic (rounds, damage, health, rigged ending)
- [ ] Part 2: boss entity, menu screen, health bar
- [ ] Part 3: music-note beam and sound effects

## Try the battle logic (no Minecraft needed)

```
javac -d out src/main/java/com/example/candyshell/battle/*.java
java -cp out com.example.candyshell.battle.TestBattle
```

## Adding rhymes

Open `RoundBank.java` and copy one `round(...)` block. Each option has a power from 0 (weak) to 3 (fire).

## Credits and legal

All characters, names and rhymes are original. No copyrighted songs are used.

## License

MIT
