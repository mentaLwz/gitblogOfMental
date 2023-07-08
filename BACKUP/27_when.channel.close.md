# [when channel close](https://github.com/mentaLwz/gitblogOfMental/issues/27)

	// When the channel is closed, the receive will immediately return.
	// When we receive on a channel that is open, we cannot return until we receive the data
	// signal. But if we receive on a channel that is closed, we are able to receive the signal
	// without data. We know that event is occurred. Every receive on that channel will immediately
	// return.

https://github.com/hoanhan101/ultimate-go/blob/master/go/concurrency/channel_1.go