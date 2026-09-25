1. Put tools in tool holders
2. Set tool offsets using tool probe
3. Set fixture offset(s) with touch probe (usually G54)
4. Load program
5. Check that tool numbers in program match tools in machine
6. Check that appropriate fixture offset is loaded
7. Load stock in the machine
8. Proof the part - test the program with air cuts. One easy way to do this is to add a height to the G54 Z value sufficient to make sure that all cuts will be above the top of the part surface.
   - Use rapid and feed override at the beginning of the program to make sure that the initial Z axis moves are safe
   - You can also use single block mode
   - Keep your hand close to the emergency stop in case the program doesn't do what you expect
9. Reset G54 to the correct value
10. Run the program for the first time - follow the precautions in step 8 to make sure that nothing unexpected happens. You can adjust the feed rate override as needed.
