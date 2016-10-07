# ezpickle
Wrapper for cPickels in Python2.


Step 1: Add ezpickle to your PYTHONPATH:

    export PYTHONPATH=/home/andersx/dev/ezpickle/ezpickle:$PYTHONPATH

Step 2: Save a cPickle with ezpickel:

    import ezpickle
    
    something = generate_data()
    ezpickle.save(something, "something.cPickle")

Step 3: Load the same data elsewhere

    import ezpickle
    
    something_new = ezpickle.load("something.cPickle")
    do_something(something_new)

