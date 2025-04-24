This project optimizes the cutting of a rail (or similar material) to minimize waste and maximize the priority of the resulting pieces.  It takes into account customer demands for different types of rail pieces, each with a specified length, quantity, and priority.

The core functionality involves generating all possible cutting patterns of the rail, considering constraints like total length, maximum waste allowed, and the available pieces of different types and sizes.  The generated patterns are then evaluated based on two key criteria: total waste material and total priority of the produced pieces.

A key algorithm used is the Pareto front analysis. This helps identify the optimal cutting patterns that represent the best trade-off between minimizing waste and maximizing the priority.  Patterns on the Pareto front are not dominated by any other pattern; any improvement in one criterion (e.g., less waste) necessitates a decline in the other (e.g., lower priority).

The project uses visualization to represent both the rail with the cutting patterns and the Pareto front itself, allowing for easy interpretation of the results.  This helps in selecting the most suitable cutting strategy based on the specific needs and priorities of the situation.

