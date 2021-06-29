# GLFW binaries for 64-bit Windows

- i'm finish task for rotate x, rotate y and rotate z from press key q , w  or e. 
```

void KeyboardFunc(unsigned char key, int x, int y)
{
	switch (key) {
	case 27:
		exit(EXIT_SUCCESS); break;

		// nhấn phím x hoặc X để quay
	case 'q': // theo chiều x
		state = 0; break;
	case 'w': // theo chiều y 
		state = 2; break;
	case 'e': // theo chiều z
		state = 4; break; 
	case 'x':
		Alpha -= 10.0f; break;
	case 'X':
		Alpha += 10.0f; break;

	}
}

```