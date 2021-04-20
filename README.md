## About

Go x Protocol Buffers Address Book application

## Commands

* To build `*.pb.go` file from `*.proto` file:

    ```sh
    $ protoc -I=./pb --go_out=./pb ./pb/addressbook.proto
    ```

* To add a contact:

    ```sh
    $ go run ./write address-book.txt
    ```

* To list all contacts:

    ```sh
    $ go run ./read address-book.txt
    ```

## References

* https://developers.google.com/protocol-buffers/docs/gotutorial
* https://github.com/protocolbuffers/protobuf/tree/master/examples
