# Understanding Ownership

Ownership হলো Rust এর সব থেকে unique feature আর language টির বাকি অংশের ওপর বড় প্রভাব রাখে । এটি
Rust কে garbage collector ছাড়া(ই) memory safety guarantee দিতে (বা ensure করতে) enable করে ।
তাই এটা বুঝতে পারা খুবি গুরুত্বপূর্ণ যে কিভাবে ownership কাজ করে । এই chapter এ, আমরা ownership নিয়ে কথা বলবো ,
সাথে আরো কিছু related featres যেমন: borrowing, slices আর Rust কিভাবে memory তে data রাখে তা নিয়ে আলোচনা করবো ।
