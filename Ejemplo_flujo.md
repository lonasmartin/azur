```mermaid  
graph TD
		A[Inicio] --> B{que hago?};
	B -->|Yes| C[Ok];
	C -->D[repensar];
	D -->B;
	B ---->|NO| E[End];

	subgraph core logic
		B-->|Maybe| M[Think]
	end
```