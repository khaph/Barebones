# Barebones
Barebones Decoder Application

#Some Barebones codes

#factorial
init N = 3;
clear F;
incr F;
decr N;
while N not 0 do;
  copy F to G;
  while G not 0 do;
    copy N to H;
    while H not 0 do;
      incr F;
      decr H;
    end;
    decr G;
  end;
  decr N;
end;


#Sum of the first N natural number
init N = 9;
clear K;
clear R;
while N not 0 do;
  copy N to K;
  while K not 0 do;
    incr R;
    decr K;
  end;
  decr N;
end;

#Branch in Barebones
#if A != 0 then S1; else S2;
init A = 32;
clear kq;
clear invert;
incr kq;
incr invert;
while A not 0 do
  decr kq;
  decr A;
end;
while kq not 0 do
  clear S2;
  decr invert;
  decr kq;
end;
while invert not 0 do
  clear S1;
  decr invert;
end;
