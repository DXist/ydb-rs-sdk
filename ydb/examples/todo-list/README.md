# Prerequisites

Ydb is available at `grpc://localhost:2136?database=local`. Custom connection string could be specified via `YDB_CONNECTION_STRING` env variable.

# Initialize todo list database

cargo run -p todo-list initdb

# Add todo item

cargo run -p todo-list add 1 my todo item

# List todo items

cargo run -p todo-list list

# Mark a todo item as done

cargo run -p todo-list markdone 1

# Remove a todo item

cargo run -p todo-list remove 1

# Clear todo list database

cargo run -p todo-list cleardb
