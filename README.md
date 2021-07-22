My poc topic is Canteen-automation-system.In poc I have cloned the substrate-node-template and in node-template I have added 3-pallet.So that pallet name is MyCanteen, bill and custbill.In MyCanteen I have done some changes in lib.rs mock.rs and test.rs.Done all the function in lib.rs file which is help to display on the output.MyCanteen pallet is define for menu of canteen it can display some dishes list and we can write a amount of particular dish.Next one is custbill as per same as Mycanteen changes in some rs file and cargo.toml file so in this pallet information about the customer taken some parameter display the details of customer.And the last one is bill pallet is calculate all the ordering food and display the calculated amount in event.So I have runnable code for this poc result display on event as well as in block details.Also I have used frontend which cloned on the github my result also display on the frontend.

Documentation:-
https://substrate.dev/docs/en/knowledgebase/getting-started/

for windows:-
https://substrate.dev/docs/en/knowledgebase/getting-started/windows-users

#Authors
[@parityteam](https://substrate.dev/docs/en/tutorials/create-your-first-substrate-chain/)


Installations:

sudo apt update
# May prompt for location information
sudo apt install -y git clang curl libssl-dev llvm libudev-dev

curl https://getsubstrate.io -sSf | bash -s -- --fast

# Install
curl https://sh.rustup.rs -sSf | sh
# Configure
source ~/.cargo/env

rustup default stable
rustup update
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly

Deployment
# Run a temporary node in development mode
./target/release/node-template --dev --tmp

#Run for frontend :-
yarn start






