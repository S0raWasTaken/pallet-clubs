# Pallet-Clubs
It's a simple pallet to add users to different clubs

## Testing
Either you can test it using `cargo test` or adding it to your custom runtime.

## Usage
It should be straight forward. 
Assign an accountid to a club using the `assign_club` extrinsic or remove it assigning `Clubs::Empty`.

> Quick note: When assigning `Clubs::Empty`, the value is removed from storage, since it's pointless storing it.
