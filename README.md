# Maze Trap - A Text-Based Adventure Game

Welcome to **Maze Trap**, a simple and exciting text-based adventure game where your goal is to find the key and reach the exit. Navigate through a maze of rooms, collect important items like the torch and key, and try to escape. Be careful, though, as some items might deceive you!

## Gameplay

In this game, you can move around different locations within the maze and interact with objects. Your objective is to find the key and use it to unlock the exit. The torch may help you see in dark rooms, so make sure to pick it up if you find it!

### Available Commands

- **go `<compass direction>`**: Move to a different room in the specified direction (`north`, `east`, `south`, or `west`).
- **take `<object>`**: Pick up an object that you find in the current room.
- **drop `<object>`**: Drop an object from your inventory into the current room.
- **inventory**: View the items you are currently carrying.
- **quit**: Quit the game.

### Locations

- **Maze**: The starting location, where you can explore in different directions.
- **Maze Key**: A dark room where you might find the key if you have a torch.
- **Maze Torch**: A room containing the torch, which is essential for exploring dark rooms.
- **Maze Challenge**: A tricky room where you may find a deceptive fake key.
- **Maze Dead End**: A room that might seem like a dead end, but with the right items, you may discover a secret.
- **Maze Exit**: The final room where you can escape the maze if you have the key.

## How to Play

1. **Navigate the Maze**: Use the `go` command followed by a direction (north, east, south, or west) to move between rooms.

2. **Collect Items**: Use the `take` command followed by the item name to pick up items. The items you carry can help you progress through the maze.

3. **Use Your Inventory**: Check your inventory with the `inventory` command to see what you're carrying. You can also drop items with the `drop` command.

4. **Escape the Maze**: Find the key and navigate to the maze exit to escape. Make sure you have the necessary items to unlock the exit!

5. **Quit the Game**: If you want to quit, simply type `quit`.

### Example Commands

- `go north`
- `take torch`
- `drop fake-key`
- `inventory`
- `quit`

## Installation

1. **Download or Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/maze-trap.git
    ```

2. **Navigate to the Game Directory**:
    ```bash
    cd maze-trap
    ```

3. **Run the Game**:
    ```bash
    python maze_trap.py
    ```

## Contributing

Feel free to submit issues or pull requests to improve the game! Contributions are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thank you for trying out Maze Trap! We hope you enjoy the challenge of escaping the maze.
