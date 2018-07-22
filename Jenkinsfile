// This shows a simple build wrapper example, using the Timestamper plugin.
node {
    // Adds timestamps to the output logged by steps inside the wrapper.
    timestamps {
        stage "Checkout"
        echo "Let's get some code"

        // Just some echoes to show the timestamps.
        stage "First echo"
        echo "Hey, look, I'm echoing with a timestamp!"

        // A sleep to make sure we actually get a real difference!
        stage "Sleeping"
        sleep 5

        // And a final echo to show the time when we wrap up.
        stage "Second echo"
        echo "Wonder what time it is now?"
    }
}
