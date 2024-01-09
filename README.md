```pascal
[...]
function PreencherDev: TDesenvolvedor;
var Conhecimento: TConhecimento;
begin
  Result := TDeveloper.create;
  Result.Nome := "Rafael Gustavo Semenzin";
  Result.Area := "Desenvolvedor";
  Result.Trabalho := "Rac Systems";
  Result.Local := "São José do Rio Preto - SP";

  Conhecimento := TConhecimento.create
  Conhecimento.Area := "Delphi";
  Conhecimento.TempoAtuando := "5 anos";

  Result.Conhecimentos.add(Conhecimento);
end;
[...]
```
