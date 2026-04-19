using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Lab9.Purple
{
    public class Task4 : Purple
    {
        private string _output; protected (string, char)[] _codes;
        public string Output => _output; public (string, char)[] Codes => _codes;
        public Task4(string text, (string, char)[] codes) : base(text)
        {
            _output = string.Empty; _codes = codes;
        }
        public override void Review()
        {
            string str = _input;
            for (int i = 0; i < _codes.Length; i++)
                str = str.Replace(_codes[i].Item2 + "", _codes[i].Item1);
            _output = str;

        }
        public override string ToString()
        {
            return _output;
        }
    }
}
