# Initialize Template

    prepare.sh && rm prepare.sh

# Run Application

    cargo run

# Automated Tests
This project runs automated tests and lints before each
git push action. If you want to trigger tests manually,
run:

    cargo test

# Linting
This project runs automated tests and lints before each
git push action. If you want to trigger linting manually,
run:

    cargo clippy -- -D warnings && cargo fmt -- --check


