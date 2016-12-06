program smsky;
uses crt;
var sub:text;
    ch:char;
    n:word;
begin
clrscr;
assign(sub,'smsky.txt');
reset(sub);
n:=0;
while not(eof(sub)) do begin
                       n:=n+1;
                       repeat
                       read(sub,ch);
                       write(ch);
                       until ord(ch)=10;
                       end;
writeln(n);
readln;
close(sub);
end.
