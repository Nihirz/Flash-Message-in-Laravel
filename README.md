# Flash-Message-in-Laravel


First You have to create this file as a blade.php than

you have to include this file in header file
like this one
@include('flash-message')


after this you have to just add class on controller like this one

return redirect()->back()->with('success','Your Message Successfully sent, We Contact You Soon !');
