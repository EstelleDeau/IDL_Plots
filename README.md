# IDL_Plots

; Name:
;	legend
; Purpose:
;	This procedure makes a legend for a plot.  The legend can contain
;	a mixture of symbols, linestyles, and filled polygons (usersym).
; Examples:
;	The call:
;		legend,['diamond','asterisk','square'],psym=[4,2,6]
;	produces:
;		-----------------
;		|		|
;		|  <> diamond	|
;		|  *  asterisk	|
;		|  [] square	|
;		|		|
;		-----------------
;	Each symbol is drawn with a plots command, so they look OK.
; Modification history:
;	write, 24-25 Aug 92, F K Knight (knight@ll.mit.edu)
;	allow omission of items or omission of both psym and linestyle, 26 Aug 92, FKK
;   add corners keyword to facilitate multi-column legends, 26 Aug 92, FKK
;   add plotsym symbols and allow multi color symbols from different color tables, 6 Fev 2007 Estelle A Deau (estelle.deau@cea.fr)
;   add triangle left and right symbols 23 july 2007 EAD
;   add other symbols 13 may 2013 EAD
